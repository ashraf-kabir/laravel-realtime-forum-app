<template>
  <v-toolbar>
    <!-- <v-toolbar-side-icon></v-toolbar-side-icon> -->
    <v-toolbar-title>Brand</v-toolbar-title>
    <v-spacer></v-spacer>
    <div class="hidden-sm-and-down">
      <v-btn flat>Forum</v-btn>
      <v-btn flat>Ask Question</v-btn>
      <v-btn flat>Category</v-btn>
      <router-link to="/login">
        <v-btn flat>Login</v-btn>
      </router-link>
    </div>
  </v-toolbar>
</template>

<script>
export default {
    
}
</script>

<style lang="stylus">

</style>