<template>
  <div class="container" id="home">
    <div class="intro">
      <h2>I'm Obinna</h2>
      <h4>Software Developer & Data Scientist</h4>
    </div>
    <div class="image">
      <img src="@/assets/image.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Summary"
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  font-family: arial, sans-serif;
}
.intro {
  align-self: center;
}
h2 {
  font-size: 70px;
  font-weight: 100;
  color: black;
  margin-bottom: 5px;
}

h4 {
  font-size: 25px;
  color: gray;
  margin-top: 10px;
}
@media (max-width: 900px) {
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .intro{
    padding-top: 40px;
  }

}
</style>