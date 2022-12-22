<template>
  <div class="stickyBody">
    <div class="sticky" onClick="javascript:window.scrollTo(0,0)">
      <div>지미 앱</div>
      <div>
        받기

        <span>
          <img src="../assets/downBtn.svg" alt="" />
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.stickyBody {
  z-index: 10;
  position: sticky;
  width: 100vw;
  top: calc(100vh - 336px);
}

.sticky {
  position: absolute;
  top: 31px;
  right: 150px;
  width: 186px;
  height: 186px;
  border-radius: 50%;
  background: #b8f401;
  filter: drop-shadow(0px 20px 20px rgba(81, 88, 91, 0.2));
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 700;
  font-size: 30px;
  line-height: 36px;
  letter-spacing: -0.4px;

  color: #005d22;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.sticky img {
  width: 28px;
  height: 31px;
}

@media (max-width: 1044px) {
  .stickyBody {
    top: calc(100vh - 206px);
  }
  .sticky {
    right: 36px;
    width: 120px;
    height: 120px;

    font-size: 20px;
    line-height: 24px;
  }
  .sticky img {
    width: 16.3px;
    height: 18px;
  }
}
</style>
