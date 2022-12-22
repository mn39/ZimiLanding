<template>
  <div class="footerBody">
    <div class="line"></div>
    <div class="container1044">
      <div class="zimiNDown">
        <div class="zzime">
          <div class="greenZ">
            <img src="../assets/greenZ.svg" alt="" />
          </div>
          <img class="greenZime" src="../assets/greenZime.svg" alt="" />
        </div>
        <div class="downContainer">
          <div class="downText">지미 앱 다운로드하기</div>

          <div class="appDownloadContainer">
            <div
              class="appDownload"
              onclick="location.href='https://apps.apple.com/kr/app/%EC%A7%80%EB%AF%B8-%EC%9D%BC%EC%83%81%EC%97%90%EC%84%9C-%EC%8B%9C%EC%9E%91%ED%95%98%EB%8A%94-%EC%A7%80%EA%B5%AC-%EC%A7%80%ED%82%B4%EC%9D%B4/id1632998684'"
            >
              <img class="appStoreLogo" src="../assets/appStore.svg" alt="" />
              <div class="appDownText">App Store</div>
            </div>
            <div
              class="appDownload"
              onclick="location.href='https://play.google.com/store/apps/details?id=net.greenstaff.android.app'"
            >
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
      <div class="secondLine"></div>
      <div class="service">
        <span>서비스 문의</span>
        <img src="../assets/serviceCheck.svg" alt="" />
        <span>제휴 문의</span>
        <img src="../assets/serviceCheck.svg" alt="" />
        <span>개인정보 처리방침</span>
        <img src="../assets/serviceCheck.svg" alt="" />
        <span>이용약관</span>
        <img src="../assets/serviceCheck.svg" alt="" />
      </div>
      <div class="copyRight">Copyright © 2022 ZIME All Rights Reserved.</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.footerBody {
  margin-top: 56px;
  width: 100vw;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.line {
  height: 1px;
  width: 100vw;
  background: #d8dee4;
}
.container1044 {
  width: 1044px;
  padding-left: 36px;
}

.zimiNDown {
  height: 220px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: stretch;
}
.greenZ {
  height: 66px;
  width: 66px;
  border-radius: 15px;
  background: #ffffff;
  box-shadow: 0px 4px 16px rgba(0, 0, 0, 0.1);
  display: flex;
  justify-content: center;
  align-items: center;

  margin-right: 17.11px;
}
.greenZime {
  width: 180.71px;
  height: 53.98px;
}
.zzime {
  /* margin-top: 77px; */
  margin-left: 34px;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.downContainer {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.downText {
  margin-top: 56px;
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 100%;
  letter-spacing: -0.4px;

  color: #222222;
}
.appDownloadContainer {
  margin-top: 12px;
  display: flex;
  flex-direction: row;
  z-index: 1;
}
.appDownload:nth-child(1) {
  margin-right: 14.26px;
}
.appDownload {
  box-sizing: border-box;
  width: 262.74px;
  height: 76px;
  background: #ededee;
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
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 500;
  font-size: 30px;
  line-height: 100%;
  text-align: center;
  letter-spacing: -0.4px;

  color: #222222;
}

.secondLine {
  position: relative;
  left: 36px;
  width: 1044px;
  height: 1px;
  background: #d8dee4;
}
.service {
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 26px;
  letter-spacing: -0.4px;

  color: #51585b;
  margin-top: 30px;
  margin-left: 71px;

  text-align: left;
}

.service img {
  margin-left: 6px;
  margin-right: 34px;
}
.copyRight {
  margin-left: 71px;
  margin-top: 26px;
  margin-bottom: 113px;
  text-align: left;
  font-family: "Pretendard";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 26px;
  letter-spacing: -0.4px;

  color: #ada9a9;
}
@media (max-width: 1044px) {
  .appDownload:nth-child(1) {
    margin-right: 22px;
  }
  .appDownload {
    width: 230px;
    height: 66.53px;
  }
  .container1044 {
    box-sizing: border-box;
    width: 100%;
    padding: 0 36px;
    display: flex;
    flex-direction: column;
  }
  .secondLine {
    left: 0;
    width: auto;
  }
}

@media (max-width: 722px) {
  .zimiNDown {
    flex-direction: column;
    align-items: center;
    height: auto;
    justify-content: flex-start;
  }
  .downText {
    display: none;
  }
  .zimiNDown {
    margin-top: 32px;
  }
  .downContainer {
    margin-top: 32px;
    margin-bottom: 36px;
  }
  .service {
    font-size: 16px;
    line-height: 26px;
  }
  .copyRight {
    font-size: 16px;
    line-height: 26px;
  }
  .service img {
    margin-left: 6px;
    margin-right: 24px;
  }
  .greenZ {
    height: 52px;
    width: 52px;
  }
  .greenZ img {
    width: 26px;
    height: 30px;
  }
  .greenZime {
    width: 142.5px;
    height: 42.5px;
  }
  .appDownload {
    width: 169px;
    height: 49px;
  }
  .appStoreLogo {
    width: 16.8px;
    height: 20.65px;
  }
  .googlePlayLogo {
    width: 16.2px;
    height: 18.4px;
  }
  .appDownText {
    font-size: 18px;
  }
}
@media (max-width: 600px) {
  .service {
    margin-left: 0px;
    font-size: 12px;
  }
  .copyRight {
    margin-left: 0px;
    font-size: 12px;
  }
}
</style>
