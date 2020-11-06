<template>
  <v-app>
    <v-main>
          <router-view />
          <v-btn>
            hello
            <v-icon>edit</v-icon>
          </v-btn>
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
