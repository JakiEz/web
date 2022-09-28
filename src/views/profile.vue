<template>
  <div>
    <h1>Certificate</h1>
    <div class="box">
      <img class="pic" src="../pic/c.jpg" />
      <img class="pic" src="../pic/python1.jpg" />
      <img class="pic" src="../pic/python2.jpg" />
      <img class="pic" src="../pic/CPALL.jpg" />
      <img class="pic" src="../pic/stem.jpg" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-family: "Courier New";
  color: rgba(38, 41, 37, 0.849);
}
.pic {
  width: 400px;
  height: 250px;
  padding-right: 20px;
  box-shadow: -10px 5px 10px grey;
  top: 0;
  cursor: pointer;
  transition-property: transform;
  transition-duration: 1s;
}
.pic:hover {
 transform: scale(1.1, 1.1);
}

.box {
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  padding-top: 20px;
}
</style>
