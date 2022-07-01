<script>
import ContactForm from "@/components/ContactForm.vue";
import NavBar from "@/components/NavBar.vue";

export default {
  name: "ContactPage",
  components: {
    ContactForm,
    NavBar,
  },
  created() {
    document.title = "Contact - jmxi.art";
  },
};
</script>

<template>
  <NavBar />
  <ContactForm />
</template>
