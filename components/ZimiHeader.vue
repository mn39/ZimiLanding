<template>
  <div class="headerContainer">
    <div class="header">
      <img src="../assets/ZIME.svg" class="zimiLogo" alt="" />
      <div class="contactUs">Contact us</div>
    </div>
    <div class="headerLine"></div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.headerContainer {
  width: 100vw;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  position: fixed;
  background: #ffffff;
  z-index: 9;
}
.header {
  height: 64px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.zimiLogo {
  width: 100px;
  height: 31.44px;
  margin-right: 788px;
}
.contactUs {
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: -0.4px;

  color: #000000;
}

.headerLine {
  height: 1px;
  background: #d8dee4;
  transform: matrix(1, 0, 0, -1, 0, 0);
}

@media (max-width: 1044px) {
  .header {
    padding: 0 36px;
    justify-content: space-between;
  }
  .zimiLogo {
    margin: 0;
  }
}
</style>
