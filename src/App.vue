<template>
  <div id="app">
    <nav id="menu-list">
      <router-link to="/" tag="a">Home</router-link>
      <router-link to="/AboutUs" tag="a">About Us</router-link>
    </nav>
    <div id="top-bar">
    
      <div id="logo"></div>
    
    </div>
    <router-view></router-view>
  </div>
</template>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script>
export default {
  name: 'app'
}
</script>

<style>

  @import "https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css";
  @import "assets/css/common.css";
</style>
