<template>
  <div>
    <div class="zimiMain">
      <div class="mainFlexContainer">
        <div class="mainFlex">
          <h1 class="title">
            일상에서 시작하는<br />
            지구지킴이, 지미
          </h1>
          <h2 class="detail">
            지미는 당신의 작은 실천으로 시작합니다.<br />지구를 위한 미션을 다른
            사람들과 함께 하며<br />환경 보호를 재밌고, 힙하게 실천하세요!
          </h2>
          <div class="appDownloadContainer">
            <a
              class="appDownload"
              href="https://apps.apple.com/kr/app/%EC%A7%80%EB%AF%B8-%EC%9D%BC%EC%83%81%EC%97%90%EC%84%9C-%EC%8B%9C%EC%9E%91%ED%95%98%EB%8A%94-%EC%A7%80%EA%B5%AC-%EC%A7%80%ED%82%B4%EC%9D%B4/id1632998684"
            >
              <img
                class="appStoreLogo"
                src="../assets/appStore.svg"
                alt="앱스토어 로고"
              />
              <h6 class="appDownText">App Store</h6>
            </a>
            <a
              class="appDownload"
              href="https://play.google.com/store/apps/details?id=net.greenstaff.android.app"
            >
              <img
                class="googlePlayLogo"
                src="../assets/googlePlay.svg"
                alt="구글 플레이스토어 로고"
              />
              <h6 class="appDownText">Google Play</h6>
            </a>
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
          <img src="../assets/img-07.svg" class="foot" alt="재활용 그림" />
        </div>
        <div class="ellipseBicycle">
          <img src="../assets/img-08.svg" class="bicycle" alt="자전거 그림" />
        </div>
        <div class="ellipseRecycle">
          <img src="../assets/img-09.svg" class="recycle" alt="재활용 그림" />
        </div>
        <img
          class="people"
          src="../assets/people-05.svg"
          alt="지미 사람 그림"
        />
      </div>
    </div>
    <div class="mainBot">
      <h3 class="detail2">
        지미에서는 당신의 활동을 잊지 않아요.<br />
        당신이 실천한 친환경 활동을 정량적으로 기록하고 측정해드립니다.<br />
        활동을 다른 사람들과 나누고, 더 깨끗한 지구를 만들어가요. <br /><br />
        지미에서 기업들과 함께하는 활동도 참여해보세요!<br />
        기업과 함께하는 더 의미있고 영향력 있는 활동을 알려드릴게요.
      </h3>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="css" scoped>
a {
  text-decoration: none;
}
.zimiMain {
  height: 1080px;
  overflow: hidden;
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
  font-family: 'Pretendard';
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

  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 26px;
  line-height: 131%;

  letter-spacing: -0.4px;

  color: #000000;
}
.hill {
  position: absolute;
  left: -50vw;
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
  background: #b8f400;
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
/*asdfasdfasdf */
.relativeDiv {
  position: relative;
  width: 0;
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
  margin-top: 329px;
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

.appDownload:hover {
  background: #a5e400;
  border: 1px solid #a5e400;
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
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 30px;
  line-height: 100%;
  text-align: center;
  letter-spacing: -0.4px;

  color: #222222;
}

.mainBot {
  padding-top: 90px;

  width: 100vw;
  height: 387px;

  background: linear-gradient(
    180deg,
    rgba(184, 244, 0, 1) 0%,
    rgba(184, 244, 0, 0) 100%
  );
}

.detail2 {
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 26px;
  line-height: 131%;
  text-align: center;
  letter-spacing: -0.4px;

  color: #000000;
}

@media (max-width: 1044px) {
  .mainFlexContainer {
    padding: 0 36px;
    align-items: stretch;
  }
  .mainFlex {
    width: auto;
  }
  .title {
    font-size: 70px;
    line-height: 84px;
  }
  .detail {
    z-index: 5;
    font-size: 22px;
    line-height: 30px;
  }

  .ellipseBicycle {
    top: -512.94px;
    left: -81px;
    width: 203.21px;
    height: 203.21px;
    border-radius: 50%;
  }
  .bicycle {
    width: 132.24px;
    height: 110.3px;
  }

  .ellipseFoot {
    top: -866px;
    left: 242.06px;
    width: 245.99px;
    height: 245.99px;
  }

  .foot {
    width: 145.32px;
    height: 165.62px;
  }

  .ellipseRecycle {
    top: -338.34px;
    left: 318.62px;
    width: 166.83px;
    height: 166.83px;
  }

  .recycle {
    width: 63.23px;
    height: 130.46px;
  }
  .people {
    top: -785px;
    width: 299px;
    height: 694px;
    left: 50.44px;
  }

  .appDownloadContainer {
    margin-top: 368px;
  }
  .appDownload:nth-child(1) {
    margin-right: 22px;
  }
  .appDownload {
    width: 230px;
    height: 66.53px;
  }
}

@media (max-width: 722px) {
  .title {
    font-size: 50px;
    line-height: 60px;
  }
  .detail {
    font-size: 20px;
    line-height: 28px;
  }

  .ellipseBicycle {
    top: -518.14px;
    left: -73px;
    width: 174.89px;
    height: 174.89px;
    border-radius: 50%;
  }
  .bicycle {
    width: 113.82px;
    height: 94.92px;
  }

  .ellipseFoot {
    top: -822px;
    left: 203.32px;
    width: 211.71px;
    height: 211.71px;
  }

  .foot {
    width: 125.07px;
    height: 142.54px;
  }

  .ellipseRecycle {
    top: -367.87px;
    left: 270.94px;
    width: 143.58px;
    height: 143.58px;
  }

  .recycle {
    width: 54.42px;
    height: 112.28px;
  }
  .people {
    top: -752px;
    width: 257px;
    height: 597px;
    left: 40px;
  }
  .appDownloadContainer {
    margin-top: 406px;
  }

  .detail2 {
    font-size: 20px;
    line-height: 170%;
  }
}

@media (max-width: 600px) {
  .title {
    font-size: 40px;
    line-height: 48px;
  }
  .detail {
    font-size: 16px;
    line-height: 22px;
  }

  .ellipseBicycle {
    top: -518.14px;
    left: -73px;
    width: 174.89px;
    height: 174.89px;
    border-radius: 50%;
  }
  .bicycle {
    width: 113.82px;
    height: 94.92px;
  }

  .ellipseFoot {
    top: -822px;
    left: 203.32px;
    width: 211.71px;
    height: 211.71px;
  }

  .foot {
    width: 125.07px;
    height: 142.54px;
  }

  .ellipseRecycle {
    top: -367.87px;
    left: 270.94px;
    width: 143.58px;
    height: 143.58px;
  }

  .recycle {
    width: 54.42px;
    height: 112.28px;
  }
  .people {
    top: -752px;
    width: 257px;
    height: 597px;
    left: 40px;
  }
  .appDownloadContainer {
    margin-top: 436px;
  }
  .appDownload:nth-child(1) {
    margin-right: 14.26px;
  }
  .appDownload {
    width: 150px;
    height: 45px;
  }
  .appStoreLogo {
    width: 18px;
    height: 21px;
    margin-right: 6px;
  }

  .googlePlayLogo {
    width: 15px;
    height: 19px;
    margin-right: 5px;
  }
  .appDownText {
    font-size: 18px;
  }
  .detail2 {
    font-size: 18px;
    line-height: 170%;
  }
}
@media (max-width: 430px) {
  .zimiMain {
    height: 960px;
  }
  .mainFlexContainer {
    height: 960px;
  }
  .title {
    font-size: 35px;
  }
  .detail2 {
    font-size: 14px;
  }
  .detail {
    margin-top: 17px;
  }
  .appDownloadContainer {
    margin-top: 356px;
  }
  .ellipseBicycle {
    top: -442px;
    left: -64px;
    width: 84px;
    height: 84px;
    border-radius: 50%;
  }
  .bicycle {
    width: 54.88px;
    height: 45.77px;
  }

  .ellipseFoot {
    top: -588px;
    left: 69px;
    width: 102.09px;
    height: 102.09px;
  }

  .foot {
    width: 60px;
    height: 69px;
  }

  .ellipseRecycle {
    top: -370px;
    left: 102px;
    width: 69px;
    height: 69px;
  }

  .recycle {
    width: 26.24px;
    height: 54.14px;
  }
  .people {
    top: -555px;
    width: 124px;
    height: 288px;
    left: -9px;
  }
  .mainBot {
    padding-top: 0px;
  }
}
</style>
