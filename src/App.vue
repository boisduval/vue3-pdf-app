<template>
  <PdfApp style="height: 90vh" pdf="/sample.pdf"></PdfApp>
</template>

<script>
import PdfApp from "vue3-pdf-app";
import "vue3-pdf-app/dist/icons/main.css";
export default {
  name: "App",
  components: {
    PdfApp,
  },
};
</script>
