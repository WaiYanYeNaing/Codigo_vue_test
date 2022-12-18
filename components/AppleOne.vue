<template>
  <div class="apple_one_main_container">
    <div class="apple_one_container">
      <!-- Left Image -->
      <div class="left_img_container">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/bundle__e93qdcv7mtm6_large.jpg"
          alt="left_img"
        />
      </div>

      <!-- Right title_copy -->
      <div class="right_title_copy_container">
        <!-- One -->
        <img
          class="one_img"
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/apple_one__b0modw3b87xy_large.png"
          alt="one"
        />
        <!-- Headling -->
        <div class="headline">
          Bundle Apple TV+ with <br />
          up to five other great services. <br />
          And enjoy more for less.
        </div>
        <!-- Try Free Button -->
        <div class="try_free_container">Try Apple One free^</div>
        <!-- Learn More -->
        <div class="learn_more_container">
          <div class="learn_more">Learn more</div>
          <img
            src="https://img.icons8.com/material-outlined/18/0f64ba/forward.png"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import '~assets/variables';
.apple_one_main_container {
  width: 97%;
  margin: 0 auto;
  background-color: #fff;

  //   Apple One
  @media only screen and (max-width: 1000px) {
    .apple_one_container {
      max-width: 733px !important;
    }
  }
  .apple_one_container {
    max-width: 1360px;
    display: flex;
    flex-wrap: wrap;
    // justify-content: space-between;
    margin: 0 auto;
    background-color: #f5f5f7;

    .left_img_container {
      margin-left: 7.5%;
      width: 39%;
      //   width: 544px;
      height: 330px;
      margin-top: 126px;
      margin-bottom: 128px;
      //   min-width: 544px;
      img {
        width: 100%;
      }
    }
    @media only screen and (max-width: 1000px) {
      .left_img_container {
        margin-top: 96px;
        margin-bottom: 98px;
        height: auto;
      }
    }
    .right_title_copy_container {
      display: flex;
      width: 48.5%;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      .one_img {
        width: 102px;
        height: 33px;
      }
      @media only screen and (max-width: 1000px) {
        .one_img {
          width: 62px;
          height: 21px;
        }
      }
      .headline {
        font-size: clamp(25px, 3.5vw, 48px);
        line-height: 1.0834933333;
        font-weight: 700;
        letter-spacing: -0.003em;
        margin-top: 27px;
        margin-bottom: 13px;
      }
      .try_free_container {
        margin-top: 20px;
        margin-bottom: 29px;
        display: inline-block;
        border-radius: 980px;
        min-width: 26px;
        padding: 12px 22px;
        font-size: 14px;
        line-height: 1.4285914286;
        letter-spacing: -0.016em;
        font-weight: 700;
        cursor: pointer;
        color: #fff;
        background-color: #1d1d1f;
      }
      .learn_more_container {
        display: flex;
        align-items: center;
        width: 110px;
        .learn_more {
          color: #06c;
          font-size: 19px;
          line-height: 1.2105263158;
          font-weight: 400;
        }
      }
    }
    @media only screen and (max-width: 720px) {
      .left_img_container {
        width: 50%;
        margin: 45px auto 0;
      }
      .right_title_copy_container {
        width: 100%;
        margin-bottom: 77px;
      }
    }
  }
}
</style>
