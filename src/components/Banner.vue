<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style>
#main-banner{
  background-image: url("../components/img/banner.jpg");
  background-position:  0 -610px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
#main-banner h1{
  color: #fff;
  text-align: center;
  font-size: 60px;
  background-color: rgba(72, 61, 61, 0.4);
  padding: 20px 40px;
}
</style>