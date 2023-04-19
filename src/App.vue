<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          class="shrink mr-2"
          alt="Vuetify Logo"
          contain
          src="@/assets/logo.png"
          transition="scale-transition"
          width="40"
        />


        <div
          class="text-overline"
        >
          Dockerfile Generator
        </div>
      </div>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
