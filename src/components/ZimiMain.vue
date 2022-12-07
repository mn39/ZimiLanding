<template>
  <div>
    <div class="zimiMain">
      <div class="mainFlexContainer">
        <div class="mainFlex">
          <h1 class="title">
            일상에서 시작하는<br />
            지구지킴이 생활, 지미
          </h1>
          <h3 class="detail">
            지미는 미션을 통해 지구를 위한<br />
            당신의 작은 실천의 시작에 함께합니다. 리워드를 통해 <br />
            환경보호를 재밌게, 꾸준히 지속하도록 돕습니다.<br />
            보상, 동기, 패널티, 커뮤니티를 핵심 요소로 <br />
            지구 지킴이 습관이 되는 것을 목표로 합니다.
          </h3>
          <div class="appDownloadContainer">
            <div class="appDownload">
              <img class="appStoreLogo" src="../assets/appStore.svg" alt="" />
              <div class="appDownText">App Store</div>
            </div>
            <div class="appDownload">
              <img
                class="googlePlayLogo"
                src="../assets/googlePlay.svg"
                alt=""
              />
              <div class="appDownText">Google Play</div>
            </div>
          </div>
        </div>
      </div>
      <div class="relativeDiv">
        <div class="hill">
          <div class="ellipseContainer">
            <div class="ellipse"></div>
          </div>
        </div>
        <div class="ellipseFoot">
          <img src="../assets/img-07.svg" class="foot" alt="" />
        </div>
        <div class="ellipseBicycle">
          <img src="../assets/img-08.svg" class="bicycle" alt="" />
        </div>
        <div class="ellipseRecycle">
          <img src="../assets/img-09.svg" class="recycle" alt="" />
        </div>
        <div class="people">
          <img src="../assets/people-05.svg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.zimiMain {
  height: 1080px;
  background: linear-gradient(
    180deg,
    #f1ffe3 21.9%,
    rgba(241, 255, 227, 0) 100%
  );
}

.mainFlexContainer {
  height: 1080px;
  width: 100vw;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.mainFlex {
  height: 1080px;
  width: 972px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
}

.title {
  text-align: left;

  margin-top: 174px;
  margin-bottom: 0px;
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 700;
  font-size: 76px;
  line-height: 91px;
  letter-spacing: -0.4px;

  color: #222222;
}

.detail {
  margin-top: 48px;
  margin-bottom: 0px;
  text-align: left;

  font-family: "Pretendard";
  font-style: normal;
  font-weight: 500;
  font-size: 26px;
  line-height: 34px;
  /* or 131% */

  letter-spacing: -0.4px;

  color: #000000;
}
.hill {
  position: absolute;
  left: -50%;
  bottom: 0%;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  width: 100vw;
  overflow: hidden;
}

.ellipseContainer {
  position: relative;
  width: 100vw;
  height: 333px;
}
.ellipse {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  /* top: 747px; */
  width: 2835px;
  height: 1289.17px;
  border-radius: 50%;
  background: linear-gradient(
    180deg,
    #b8f400 4.78%,
    rgba(184, 244, 0, 0.8) 84.08%
  );
}

.ellipseBicycle {
  position: absolute;
  top: -543.5px;
  left: 64px;
  width: 221.3px;
  height: 221.3px;
  border-radius: 50%;
  background: #caf740;
  display: flex;
  justify-content: center;
  align-items: center;
}

.bicycle {
  width: 144.02px;
  height: 120.11px;
  transform: rotate(-1.65deg);
}

.ellipseFoot {
  position: absolute;
  top: -928px;
  left: 413.64px;
  width: 267.89px;
  height: 267.89px;
  border-radius: 50%;
  background: #caf740;
  display: flex;
  justify-content: center;
  align-items: center;
}

.foot {
  width: 158.26px;
  height: 180.36px;
}

.ellipseRecycle {
  position: absolute;
  top: -353.36px;
  left: 499.2px;
  width: 181.69px;
  height: 181.69px;
  border-radius: 50%;
  background: #caf740;
  display: flex;
  justify-content: center;
  align-items: center;
}

.recycle {
  width: 68.86px;
  height: 142.07px;
  transform: rotate(3.12deg);
}

.relativeDiv {
  position: relative;
  left: 50vw;
}
.people {
  position: absolute;
  width: 327px;
  height: 755px;
  top: -839px;
  left: 206.17px;
}

.appDownloadContainer {
  display: flex;
  flex-direction: row;
  margin-top: 259px;
  z-index: 1;
}
.appDownload:nth-child(1) {
  margin-right: 14.26px;
}
.appDownload {
  box-sizing: border-box;
  width: 262.74px;
  height: 76px;

  background: #ffffff;
  border: 1px solid #f1f3f5;
  backdrop-filter: blur(5px);
  /* Note: backdrop-filter has minimal browser support */

  border-radius: 10px;

  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}
.appStoreLogo {
  width: 30px;
  height: 36.76px;
  margin-right: 10px;
}

.googlePlayLogo {
  width: 26.68px;
  height: 32.48px;
  margin-right: 8.32px;
}

.appDownText {
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 500;
  font-size: 30px;
  line-height: 100%;
  text-align: center;
  letter-spacing: -0.4px;

  color: #222222;
}
</style>
