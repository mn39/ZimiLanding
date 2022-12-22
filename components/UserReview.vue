<template>
  <div class="reviewBody">
    <div class="container972">
      <div class="stat">
        <div class="oneStat">
          <div class="statTitle">총 미션 수행</div>
          <div class="tot">85,000개+</div>
        </div>
        <div class="oneStat">
          <div class="statTitle">DAU/MAU</div>
          <div class="dau">
            매일
            <span class="blueText">1200명</span>
            <span class="dauShort">, </span>
            <span class="dauLarge"><br /></span>
            매월
            <span class="blueText">9000명</span>이
            <br />
            함께하고 있어요
          </div>
        </div>
        <div class="oneStat">
          <div class="statTitle">함께 한 기업</div>
          <div class="forShort">
            <div class="storeContainer">
              <span class="oneStore">
                <div class="blueLine"></div>
                <span class="duckBun"> 덕분애 </span>
              </span>
              <span class="oneStore">
                <div class="blueLine"></div>
                <span>1.5도씨</span>
              </span>
            </div>
            <div class="plz">
              더 많은 분들과의
              <br class="dauLarge" />
              협업을 기대하고 있어요!
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="reviewTitle">생생한 유저 후기</div>
    <div class="container972 userReview">
      <div class="reviewOneRow">
        <div class="oneReview">
          <div class="reviewText">
            디자인이 깔끔해<br />
            쉽게 사용할 수 있어요.<br />
            환경을 지키면서 포인트도<br />
            쌓을 수 있어서 좋아요!
          </div>
          <div class="reviewProfile">
            <img src="../assets/userreview-40.png" alt="" />
            <div class="reviewName">김현도</div>
          </div>
        </div>
        <div class="oneReview">
          <div class="reviewText">
            <!-- 회원 가입이 간편하고 미션이 쉬워요.<br />
            적립금도 현금으로 바꿀 수 있어 일석이조<br />
            입니다. 이벤트 때문에 가입했는데<br />
            지인들에게 널리 알리고 싶어요! -->

            회원 가입이 간편하고 미션이 쉬워요. 적립금도 현금으로 바꿀 수 있어
            일석이조 입니다. 이벤트 때문에 가입했는데 지인들에게 널리 알리고
            싶어요!
          </div>
          <div class="reviewProfile">
            <img src="../assets/userreview-42.png" alt="" />
            <div class="reviewName">
              <div>김현도</div>
              <div>플레이스토어 5점</div>
            </div>
          </div>
        </div>
      </div>
      <div class="reviewOneRow">
        <div class="oneReview">
          <div class="reviewText">
            <!-- 질문에 대한 피드백이 빠르셔서 최근에<br />
            사용한 앱 중에서도 참 만족스럽습니다.<br />
            환상인지 모르겠으나, 지속가능성을 <br />
            지미에서 함께 찾아갈 수 있을 것 같아요. -->

            질문에 대한 피드백이 빠르셔서 최근에 사용한 앱 중에서도 참
            만족스럽습니다.<br />
            환상인지 모르겠으나, 지속가능성을 지미에서 함께 찾아갈 수 있을 것
            같아요.
          </div>
          <div class="reviewProfile">
            <img src="../assets/userreview-41.png" alt="" />
            <div class="reviewName">하나무</div>
          </div>
        </div>
        <div class="oneReview">
          <div class="reviewText">
            <!-- 재활용에 대한 팁을 얻을 수 있어 좋습니다.<br />
            종이 상자에 있는 테이프를 떼지 않으면<br />
            재활용이 불가능한 걸 몰랐는데, 지미 덕분에<br />
            올바른 재활용 방법을 알게 됐습니다. -->
            재활용에 대한 팁을 얻을 수 있어 좋습니다. 종이 상자에 있는 테이프를
            떼지 않으면 재활용이 불가능한 걸 몰랐는데, 지미 덕분에 올바른 재활용
            방법을 알게 됐습니다.
          </div>
          <div class="reviewProfile">
            <img src="../assets/userreview-43.png" alt="" />
            <div class="reviewName">
              <div>황도연</div>
              <div>플레이스토어 5점</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.reviewBody {
  box-sizing: border-box;
  width: 100vw;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 150px;
}
.container972 {
  width: 972px;
  display: flex;
  flex-direction: column;
}
.stat {
  display: flex;
  flex-direction: row;
}
.oneStat {
  box-sizing: border-box;
  flex: 1;
  height: 250px;
  background: #ffffff;
  box-shadow: 0px 4px 16px rgba(33, 45, 51, 0.2);
  border-radius: 10px;
  padding: 40px;
  padding-right: 3px;
}

.oneStat:nth-child(2) {
  margin: 0 16px;
}

.statTitle {
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 100%;
  text-align: left;
  letter-spacing: -0.4px;

  color: #000000;
}

.tot {
  margin-top: 62px;

  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 700;
  font-size: 46px;
  line-height: 100%;
  text-align: left;
  letter-spacing: -0.4px;

  color: #000000;
}

.dau {
  margin-top: 16px;

  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 700;
  font-size: 38px;
  line-height: 45px;
  letter-spacing: -0.4px;
  text-align: left;

  color: #000000;
}
.dauLarge {
  display: inline;
}
.dauShort {
  width: 0px;
  display: none;
}
.blueText {
  color: rgba(0, 208, 255, 1);
}

.storeContainer {
  margin-top: 31px;
  text-align: left;
}
.oneStore {
  position: relative;
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 700;
  font-size: 34px;
  line-height: 41px;
  text-align: left;
  letter-spacing: -0.4px;

  color: #000000;
}

.oneStore:nth-child(1) {
  margin-right: 14px;
}

.oneStore span {
  position: relative;
  z-index: 2;
}

.duckBun {
  left: 2px;
  width: 88px;
}
.blueLine {
  position: absolute;
  bottom: 1px;
  left: 0;
  z-index: 0;
  height: 13px;
  width: 90px;
  background: #00d0ff;
}

.oneStore:nth-child(2) .blueLine {
  position: absolute;
  bottom: 2px;
  left: 3px;
  width: 100px;
}
.plz {
  margin-top: 36px;
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  text-align: left;
  line-height: 22px;
  letter-spacing: -0.4px;

  color: #51585b;
}

.reviewTitle {
  width: 100%;
  margin-top: 112px;
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 600;
  font-size: 60px;
  line-height: 100%;
  text-align: left;
  letter-spacing: -0.4px;

  color: #000000;
}

.userReview {
  margin-top: 88px;
  /* height: 552px; */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

.reviewOneRow {
  height: 268px;
  display: flex;
  flex-direction: row;
  align-items: stretch;
}

.reviewOneRow:nth-child(1) {
  margin-bottom: 16px;
}
.oneReview {
  flex: 1;
  background: #d5f969;
  border-radius: 10px;
  padding-top: 40px;
  padding-left: 40px;
  padding-right: 40px;
}
.oneReview:nth-child(1) {
  margin-right: 28px;
}
.reviewText {
  height: 137px;
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  text-align: left;
  line-height: 29px;
  letter-spacing: -0.4px;

  color: #000000;
}
.reviewProfile {
  margin-top: 1px;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.reviewProfile img {
  width: 60px;
  height: 60px;
  margin-right: 10px;
}
.reviewName {
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 18px;
  letter-spacing: -0.4px;

  color: #000000;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.reviewName div {
  text-align: left;
}

.reviewName div:nth-child(2) {
  text-align: left;
  color: #51585b;
  margin-top: 5px;
}

@media (max-width: 1044px) {
  .reviewBody {
    margin-top: 175px;
    padding: 0 36px;
  }
  .container972 {
    width: 100%;
  }
  /* .oneStat {
    padding: 40px 0;
    text-align: center;
  } */
  .reviewTitle {
    font-size: 54px;
  }
}
@media (max-width: 975px) {
  .stat {
    flex-direction: column;
    align-items: stretch;
  }

  .oneStat {
    padding: 40px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }
  .oneStat:nth-child(2) {
    margin: 12px 0;
    padding: 24px 40px;
  }
  .oneStat:nth-child(3) {
    padding: 24px 40px 22px 40px;
  }
  .tot {
    text-align: center;
    margin: 0px;
  }
  .dau {
    font-size: 30px;
    line-height: 36px;
    text-align: right;
    margin-top: 0;
  }
  .dauLarge {
    display: none;
  }
  .dauShort {
    display: inline;
  }

  .forShort {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .storeContainer {
    margin: 0;
    text-align: right;
  }
  .plz {
    margin-top: 11px;
  }
  .reviewOneRow {
    height: 297px;
  }
  .reviewText {
    height: 166px;
  }
}
@media (max-width: 722px) {
  .reviewTitle {
    font-size: 44px;
  }
  .reviewText {
    font-size: 20px;
    line-height: 24px;
  }
  .oneReview {
    padding-left: 27px;
    padding-right: 27px;
  }
}

@media (max-width: 600px) {
  .oneStat {
    padding: 24px 24px;
  }
  .oneStat:nth-child(2) {
    padding: 24px 24px;
  }
  .oneStat:nth-child(3) {
    padding: 24px 24px 22px 24px;
  }
  .statTitle {
  }
  .tot {
    font-size: 30px;
  }
  .dau {
    font-size: 24px;
  }
  .dauLarge {
    display: inline;
  }
  .dauShort {
    display: none;
  }
  .oneStore {
    font-size: 24px;
  }
  .plz {
    font-size: 16px;
  }
  .blueLine {
    width: 100%;
  }
  .oneStore:nth-child(2) .blueLine {
    width: 100%;
  }
  .reviewText {
    font-size: 12px;
    line-height: 16px;
    height: 150px;
  }
  .oneReview {
    padding-left: 18px;
    padding-right: 18px;
    padding-top: 18px;
  }
  .reviewOneRow {
    height: 210px;
  }
  .reviewProfile img {
    width: 20px;
    height: 20px;
  }
  .reviewName {
    font-size: 8px;
    line-height: 12px;
  }
}
</style>
