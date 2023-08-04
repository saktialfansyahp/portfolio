<template>
  <v-footer>
    <v-card elevation="0" rounded="0" width="100%" class="bg-grey text-center">
      <v-card-text>
        <v-btn
          class="mx-4"
          icon="fab fa-instagram"
          variant="plain"
          color="white"
          href="https://www.instagram.com/saktialfansyah/?hl=id"
          target="_blank"
        ></v-btn>
        <v-btn
          class="mx-4"
          icon="fab fa-twitter"
          variant="plain"
          color="white"
          href="https://twitter.com/saktialfansyah"
          target="_blank"
        ></v-btn>
        <v-btn
          class="mx-4"
          icon="fab fa-linkedin"
          variant="plain"
          color="white"
          href="https://www.linkedin.com/in/sakti-alfansyah-putra-189498253/"
          target="_blank"
        ></v-btn>
        <v-btn
          class="mx-4"
          icon="fab fa-facebook"
          variant="plain"
          color="white"
        ></v-btn>
      </v-card-text>

      <v-card-text class="text-white">
        @ {{ new Date().getFullYear() }} —
        <strong>Sakti Alfansyah Putra</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
</script>

<style>
.v-footer {
  padding: 8px 0 !important;
}
</style>
