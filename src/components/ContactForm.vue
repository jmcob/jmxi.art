<template>
  <div class="hello">
    <div class="cadre">
      <h1>Me contacter</h1>
      <p>
        Si vous désirez me contacter, présentez-vous dans un bref message, en
        expliquant également le but de votre requête. <br />Je vous remercie
        pour l'intérêt que vous portez à mon travail.
      </p>

      <form ref="form" @submit.prevent="sendEmail">
        <label>Nom</label>
        <input type="text" v-model="name" name="name" placeholder="Votre nom" />
        <label>Email</label>
        <input
          type="email"
          v-model="email"
          name="email"
          placeholder="Votre e-mail"
        />
        <label>Message</label>
        <textarea
          name="message"
          v-model="message"
          cols="30"
          rows="5"
          placeholder="Message"
        >
        </textarea>

        <input type="submit" :value="send" />
      </form>
    </div>
  </div>
</template>

<script>
import emailjs from "@emailjs/browser";
export default {
  name: "ContactForm",
  data() {
    return {
      name: "",
      email: "",
      message: "",
      send: "Envoyer",
      sent: false,
    };
  },
  methods: {
    sendEmail(e) {
      let button = document.getElementsByTagName("input")[2];
      try {
        if (this.sent) {
          this.send = "Pour envoyer un message à nouveau, rechargez la page";
          button.style.backgroundColor = "#6a0dad";
          return;
        }
        emailjs.sendForm(
          "service_ym069uf",
          "template_xqvi34c",
          e.target,
          "8teXph77JJiHSkBju",
          {
            name: this.name,
            email: this.email,
            message: this.message,
          }
        );
      } catch (error) {
        console.log({ error });
      }
      // Reset form field
      this.name = "";
      this.email = "";
      this.message = "";
      this.send = "Merci pour votre message, il est transmis";
      this.sent = true;
      button.style.backgroundColor = "#4caf50";
    },
  },
};
</script>

<style scoped>
* {
  box-sizing: border-box;
}

label {
  float: left;
}
.cadre {
  padding-bottom: 20px;
  background-color: gold;
}
label,
p,
form,
h1 {
  background-color: gold;
  color: black;
}

input {
  background-color: #fff;
}

input[type="text"],
[type="email"],
textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
  background-color: #fff;
}

input[type="submit"] {
  background-color: crimson;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type="submit"]:hover {
  background-color: red;
}
</style>
