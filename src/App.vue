<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
</template>

<style>
@import url("global.css");
.container {
  margin: 0 10%;
}
</style>
