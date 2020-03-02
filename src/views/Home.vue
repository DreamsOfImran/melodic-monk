<template>
  <div>
    <div>
      <b-navbar
        toggleable="lg"
        type="dark"
        variant="transparent"
        fixed="top"
        class="m-2"
      >
        <b-navbar-brand href="#">Melodic Monk</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="mx-auto">
            <b-nav-item href="#" class="px-4" active>Home</b-nav-item>
            <b-nav-item href="#" class="px-4">About</b-nav-item>
            <b-nav-item href="#" class="px-4">Gallery</b-nav-item>
            <b-nav-item href="#" class="px-4">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

    <div id="home">
      <b-container class="h-100">
        <b-row class="h-100">
          <b-col class="my-auto text-right text-white">
            <h1>Melodic Monk</h1>
            <p>A journey with music and photography</p>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div id="about" class="bg-light">
      <b-container class="about-heading">
        <div class="text-xl-center h2">
          About Melodic Monk
        </div>
      </b-container>
      <b-container class="mt-5">
        <b-row>
          <b-col>
            <img src="../assets/img/8.jpg" height="400" width="300" />
          </b-col>
          <b-col>
            Something about me
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>
#home {
  background: url("../assets/img/sample1.jpg") no-repeat scroll center center /
    cover;
  height: 100vh;
  width: 100%;
}
#about .about-heading {
  padding-top: 50px;
}
#about img {
  object-fit: cover;
}
</style>
