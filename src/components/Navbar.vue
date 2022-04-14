<template>
  <div id="Navbar">
    <div>
      <b-nav>
        <b-nav-item><rourt-link :to=" {name : 'Home'} ">Home</rourt-link></b-nav-item>
        <b-nav-item><rourt-link :to=" {name : 'Contact'} ">Contact</rourt-link></b-nav-item>
      </b-nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  },
};
</script>

<style>
</style>