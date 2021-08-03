<template>
  <v-app>
    <v-navigation-drawer app>

    </v-navigation-drawer>

    <v-app-bar app></v-app-bar>

    <v-main>
      <v-list>
        <v-list-item>
          <v-checkbox
                  label="Todo1"
          ></v-checkbox>
        </v-list-item>
        <v-list-item>
          <v-checkbox
                  label="Todo 2"
          ></v-checkbox>
        </v-list-item>
        <v-list-item>
          <v-checkbox
                  label="Todo 3"
          ></v-checkbox>
        </v-list-item>
      </v-list>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
