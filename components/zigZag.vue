<template>
  <div class="zigZagBody">
    <h2 class="reviewTitle">차곡차곡 지구를 지켜왔어요</h2>
    <div class="hiddenContainer">
      <div class="zigZagPictureContainer">
        <transition-group name="slide">
          <img
            v-for="(n, index) in reviewList"
            v-bind:key="n"
            class="picture"
            v-bind:style="{
              left: (index - 4) * (250 + 24) - 125 + 'px',
              top: (n % 2) * 56 + 'px',
              // backgroundImage:
              //   'url(' +
              //   require(`../assets/userCarousel/userCarousel${n}.jpg`) +
              //   ')',
            }"
            v-bind:src="require(`../assets/userCarousel/userCarousel${n}.jpg`)"
            alt="실제 유저 활동 사진"
          />
          <!-- <div class="pictureID"></div>
          </span> -->
        </transition-group>
      </div>
      <!-- <div class="zigZagPictureContainer">
        <span
          v-for="(n, index) in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]"
          v-bind:key="n"
          class="picture"
          v-bind:style="{
            left: (index - 4) * (250 + 24) - 125 + 'px',
            //   backgroundColor: colorListR[n - 1],
            top: (index % 2) * 56 + 'px',
          }"
        >
          <div class="pictureID">kujy3710</div>
        </span>
      </div> -->
    </div>
    <h2 class="reviewTitle zimiStory">
      직접 만나 들어 본 <br />지미들의 이야기
    </h2>
    <div class="container996">
      <div class="forArrow">
        <div class="carousel">
          <div class="oneCarousel">
            <div class="carouselColumn">
              <div class="firstCarousel">
                <img src="../assets/phone.png" alt="" />
              </div>
              <h4 class="firstCarouselText">
                회원 가입도 간편하고 편해서 좋고 미션들도 너무 쉽고 적립금도
                현금으로 바꿀 수 있어 일석이조입니다. 이런 좋은 앱 많이 나왔으면
                좋겠습니다. 이벤트 때문에 가입했는데 지인들에게 널리 알리고
                싶어요!
              </h4>
            </div>

            <div class="carouselColumn">
              <div class="secondCarousel">
                <h3 class="carouselTitle">
                  환경도 지키고<br />제 삶에도 유용해요
                </h3>
                <h6 class="carouselText">지미를 만난지 6개월차 김진태님</h6>
              </div>
              <div class="secondCarouselText">
                <img src="../assets/phonePerson.png" alt="" />
              </div>
            </div>
          </div>
        </div>
        <!-- <carousel class="carousel" :nav="false" :items="1">
          <template slot="prev">
            <span class="prev">
              <img src="../assets/leftArrow.svg" alt="" />
            </span>
          </template>
          <div class="oneCarousel">
            <div class="carouselColumn">
              <img src="../assets/phone.png" class="firstCarousel" alt="" />
              <div class="firstCarouselText">
                회원 가입도 간편하고 편해서 좋고 미션들도 너무 쉽고 적립금도
                현금으로 바꿀 수 있어 일석이조입니다. 이런 좋은 앱 많이 나왔으면
                좋겠습니다. 이벤트 때문에 가입했는데 지인들에게 널리 알리고
                싶어요!
              </div>
            </div>

            <div class="carouselColumn">
              <div class="secondCarousel">
                <div class="carouselTitle">
                  환경도 지키고<br />제 삶에도 유용해요
                </div>
                <div class="carouselText">지미를 만난지 6개월차 김진태님</div>
              </div>
              <div class="secondCarouselText">
                <img src="../assets/phonePerson.png" alt="" />
              </div>
            </div>
          </div>
          <div class="oneCarousel">
            <div class="carouselColumn">
              <img src="../assets/phone.png" class="firstCarousel" alt="" />
              <div class="firstCarouselText">
                회원 가입도 간편하고 편해서 좋고 미션들도 너무 쉽고 적립금도
                현금으로 바꿀 수 있어 일석이조입니다. 이런 좋은 앱 많이 나왔으면
                좋겠습니다. 이벤트 때문에 가입했는데 지인들에게 널리 알리고
                싶어요!
              </div>
            </div>

            <div class="carouselColumn">
              <div class="secondCarousel">
                <div class="carouselTitle">
                  환경도 지키고<br />제 삶에도 유용해요
                </div>
                <div class="carouselText">지미를 만난지 6개월차 김진태님</div>
              </div>
              <div class="secondCarouselText">
                <img src="../assets/phonePerson.png" alt="" />
              </div>
            </div>
          </div>
          <div class="oneCarousel">
            <div class="carouselColumn">
              <img src="../assets/phone.png" class="firstCarousel" alt="" />
              <div class="firstCarouselText">
                회원 가입도 간편하고 편해서 좋고 미션들도 너무 쉽고 적립금도
                현금으로 바꿀 수 있어 일석이조입니다. 이런 좋은 앱 많이 나왔으면
                좋겠습니다. 이벤트 때문에 가입했는데 지인들에게 널리 알리고
                싶어요!
              </div>
            </div>

            <div class="carouselColumn">
              <div class="secondCarousel">
                <div class="carouselTitle">
                  환경도 지키고<br />제 삶에도 유용해요
                </div>
                <div class="carouselText">지미를 만난지 6개월차 김진태님</div>
              </div>
              <div class="secondCarouselText">
                <img src="../assets/phonePerson.png" alt="" />
              </div>
            </div>
          </div>
          <template slot="next"
            ><span class="next">
              <img src="../assets/rightArrow.svg" alt="" /></span
          ></template>
        </carousel> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      reviewList: [...Array(28).keys()],
      temp: [],
    }
  },
  methods: {
    moveLeft() {
      this.temp = this.reviewList.slice()
      // this.temp.push(this.temp.shift());
      this.temp.unshift(this.temp.pop())
      this.reviewList.splice(0, 28)

      setTimeout(() => {
        this.reviewList = this.temp
        // this.nownum = (Math.abs(((this.temp[4] - 1) % 8) - 4) % 8) + 1;
      }, 2000)
    },
    start() {
      setTimeout(() => {
        this.moveLeft()
        this.start()
      }, 2000)
    },
  },
  created() {
    setTimeout(() => {
      this.start()
    }, 2000)
  },
}
</script>

<style>
.zigZagBody {
  position: relative;
  box-sizing: border-box;
  width: 100vw;
  display: flex;
  /* overflow: hidden; */
  flex-direction: column;
  align-items: center;
  padding: 0 150px;
}
.container972 {
  width: 972px;
  display: flex;
  flex-direction: column;
}
.container996 {
  width: 996px;
  display: flex;
  flex-direction: column;
}
.reviewTitle {
  width: 100%;
  margin-top: 154px;
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 600;
  font-size: 60px;
  line-height: 100%;
  text-align: left;
  letter-spacing: -0.4px;

  color: #000000;
}
.hiddenContainer {
  width: 100vw;
  height: 476px;
  overflow: hidden;
}

.zigZagPictureContainer {
  top: 80px;
  width: 0;
  /* left: 50%; */
  position: relative;
}

.slide-enter-active,
.slide-leave-active {
  transition: all 2s linear;
}

.slide-enter {
  /* transform: translateX(274px); */
}
.slide-leave-to {
  transform: translateX(274px);
}

.picture {
  position: absolute;
  width: 250px;
  height: 340px;
  border-radius: 15px;
  background-size: cover;
  /* background-color: violet; */
  /* background-image: url("../assets/userCarousel/userCarousel1.jpg"); */
}
.pictureID {
  position: absolute;
  bottom: 20px;
  left: 20px;
}
.zimiStory {
  margin-top: 197px;
  line-height: 72px;
}
.carousel {
  position: relative;
  height: 754px;
  margin-top: 73px;
}
.oneCarousel {
  height: 754px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.carouselColumn {
  display: flex;
  flex: 1;
  flex-direction: column;
  justify-content: space-between;
  margin: 0 12px;
}
/* .carouselColumn:nth-child(1) {
  margin-right: 24px;
} */
.firstCarousel {
  height: 342px;
  background-color: aqua;
  border-radius: 10px;
}
.firstCarousel img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}
.firstCarouselText {
  margin-top: 24px;
  height: 388px;
  background: #e7eaec;
  border-radius: 10px;
  padding: 40px;

  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: -0.4px;
  color: #000000;

  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  text-align: left;
}

.secondCarousel {
  height: 215px;
  background: #f6f8fb;
  border-radius: 10px;
  padding: 32px 40px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.carouselTitle {
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 600;
  font-size: 44px;
  line-height: 53px;
  letter-spacing: -0.4px;
  color: #000000;
  text-align: left;
}
.carouselText {
  text-align: left;
  font-family: 'Pretendard';
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  letter-spacing: -0.4px;
  color: #000000;
}
.secondCarouselText {
  overflow: hidden;
  margin-top: 24px;
  height: 515px;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.secondCarouselText img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.forArrow {
  position: relative;
}
.prev {
  position: absolute;
  top: 327px;
  left: -68px;
  z-index: 2;
}
.next {
  position: absolute;
  top: 327px;
  right: -68px;
  z-index: 2;
}
@media (max-width: 1044px) {
  .zigZagBody {
    padding: 0 36px;
  }
  .container972 {
    width: 100%;
  }
  .container996 {
    width: 100%;
    /* padding: 0 12px ; */
  }
  .prev {
    left: 12px;
  }
  .next {
    right: 12px;
  }
  .reviewTitle {
    font-size: 54px;
  }
}
@media (max-width: 722px) {
  .reviewTitle {
    font-size: 44px;
  }
  .carouselTitle {
    font-size: 36px;
    line-height: 43px;
  }
  .carouselText {
    font-size: 20px;
    line-height: 24px;
  }
}

@media (max-width: 600px) {
  .reviewTitle {
    font-size: 36px;
  }
  .carouselTitle {
    font-size: 12px;
    line-height: 16px;
  }
  .carouselText {
    font-size: 8px;
    line-height: 10px;
  }
  .carousel {
    height: 372px;
  }
  .oneCarousel {
    height: 372px;
  }
  .firstCarouselText {
    height: 194px;
    font-size: 8px;
    line-height: 14px;
    padding: 16px;
  }
  .secondCarousel {
    height: 105px;
    padding: 16px;
  }
  .secondCarouselText img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .next {
    top: 160px;
  }
  .prev {
    top: 160px;
  }
}
</style>
