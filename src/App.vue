<template>
  <div id="app">
    <header class="navbar">
      <div class="logo col-md-2">Shoptime</div>
      <div class="tabs d-flex col-md-10">
        <div class="tab">HOME</div>
        <div class="tab">ORDERS</div>
        <div class="tab">PRODUCT</div>
      </div>
    </header>
    <div class="body">
      <router-view/>
    </div>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style>
@import "bootstrap/dist/css/bootstrap.min.css"
</style>
<style>
* {
  font-family: HelveticaNeue;
}
:root {
  --red-color: #D0021B;
  --yellow-color: #F5A623;
  --blue-color: #4A90E2;
  --green-color: #7ED321;
  --dark-gray: #9B9B9B;
  --background-color: #F2F2F2;
}
</style>
<style scoped>
.navbar {
  background: #000;
  color: #fff;
  font-weight: bold;
}
.logo {
  font-size: 24px;
}
.tab {
  color: var(--dark-gray);
  margin: 26px 20px 25px;
}
.tab.active {
  color: #fff;
}
.body {
  background: var(--background-color);
  padding: 30px 42px;
}
</style>
