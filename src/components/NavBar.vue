<template>
  <v-app-bar app color="black" dark flat class="px-12">
    <v-btn>
      <v-icon color="yellow" left class="mr-2">fas fa-signature</v-icon>Alfan
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')" class="text-tellow">Home</v-btn>
    <v-btn text @click="scroll('about')" class="text-tellow">About</v-btn>
    <v-btn text @click="scroll('portfolio')" class="text-tellow"
      >Portfolio</v-btn
    >
    <v-btn text @click="scroll('services')" class="text-tellow">Services</v-btn>
    <!-- <v-btn text @click="scroll('page')" class="text-tellow">Pages</v-btn> -->
    <!-- <v-btn text @click="scroll('biog')" class="text-tellow">Blog</v-btn> -->
    <v-btn text @click="scroll('contact')" class="text-tellow">Contact</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style></style>
