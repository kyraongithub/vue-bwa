<template>
  <div class="logos-wrapper">
    <h2>Find Best Logo</h2>
    <div class="item-logos">
      <img src="" alt="" />
    </div>
    <div class="item-logos">
      <img src="" alt="" />
    </div>
    <div class="item-logos">
      <img src="" alt="" />
    </div>
    <div class="item-logos">
      <img src="" alt="" />
    </div>
    <div class="item-logos">
      <img src="" alt="" />
    </div>
    <div class="item-logos">
      <img src="" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  //export untuk dipakai di comp lain
  name: "Logos",
};
</script>

<style scoped>
.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}

.item-logos {
  float: left;
  margin-right: 20px;
  margin-bottom: 20px;
  width: 150px;
  height: 150px;
  background: red;
}
</style>