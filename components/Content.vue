<template>
  <div class="div_container">
    <!-- Student Plan -->
    <v-row class="student_plan_container">
      <v-col cols="12" md="6" sm="6" class="student_plan_left">
        <h3>
          The Apple Music <br />
          Student Plan comes <br />
          with Apple TV+ for free.
        </h3>
        <div class="try_free">Try Apple Music free</div>
      </v-col>
      <v-col cols="12" md="6" sm="6" class="student_plan_right">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/student_plan__bm7yp0v4tf6u_large.jpg"
        />
      </v-col>
    </v-row>

    <!-- TV4K & AirPlay -->
    <div class="lower_container">
      <!-- TV 4K -->
      <div class="tv_4k">
        <!-- New -->
        <div class="violator-frameless">New</div>
        <img
          class="apple_tv_4k"
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/apple_tv_4k_logo__bx1mtrage32a_large.png"
          alt="appletv4k"
        />

        <!-- Headline -->
        <div class="headline">
          The Apple experience. <br />
          Cinematic in every sense.
        </div>

        <!-- Typography -->
        <div class="typography_container">
          <div class="button">Buy</div>
          <div class="learn_more">Learn more</div>
          <img
            src="https://img.icons8.com/material-outlined/18/0f64ba/forward.png"
          />
        </div>

        <!-- Image -->
        <img
          class="tv4k_img"
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/apple_tv_4k_remote__igmcbznr1w2u_large.jpg"
          alt="tv4k"
        />
      </div>

      <!-- AirPlay -->
      <div class="airplay">
        <!-- Eyebrow -->
        <div class="eyebrow">AirPlay</div>

        <!-- Headline -->
        <div class="headline">
          Bring Apple TV+ to <br />
          a screen near you.
        </div>

        <!-- Learn More -->
        <div class="learn_more_container">
          <div class="learn_more">Learn more</div>
          <img
            src="https://img.icons8.com/material-outlined/18/0f64ba/forward.png"
          />
        </div>

        <!-- Image -->
        <img
          class="airplay_img"
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/air_play__dyuvvwnd5riq_large.jpg"
          alt="airplay"
        />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.div_container {
  width: 97%;
  margin: 0 auto;
  background-color: #fff;
  //   Student Plan
  .student_plan_container {
    max-width: 1360px;
    align-items: flex-end;
    height: 530px;
    margin: 0 auto;
    background-color: #f5f5f7;
    .student_plan_left {
      max-width: 535px;
      margin-left: auto;
      height: 450px;
      h3 {
        font-size: clamp(30px, 4vw, 48px);
        line-height: 1.0834933333;
        font-weight: 700;
        letter-spacing: -0.003em;
        margin: 18px 0 1px;
        color: #1d1d1f;
      }
      .try_free {
        margin-top: 13px;
        display: inline-block;
        text-align: center;
        min-width: 28px;
        border-radius: 980px;
        background: #0071e3;
        font-size: 17px;
        line-height: 1.1764805882;
        letter-spacing: -0.022em;
        min-width: 26px;
        padding: 12px 22px;
        font-size: 14px;
        line-height: 1.4285914286;
        font-weight: 400;
        letter-spacing: -0.016em;
        font-weight: 700;
        background-color: #fff;
        color: #1d1d1f;
        cursor: pointer;
        color: #fff;
        background-color: #1d1d1f;
      }
    }
    .student_plan_right {
      background-size: contain;
      max-height: 450px;
      padding: 0px !important;
      img {
        max-width: 533px;
        width: 100%;
        height: auto;
      }
    }
    @media only screen and (max-width: 1000px) {
      .student_plan_left {
        height: 300px;
      }
    }
    @media only screen and (max-width: 599px) {
      .student_plan_left {
        height: 220px;
        margin: 0;
        display: flex;
        flex-direction: column;
        h3 {
          text-align: center;
        }
        .try_free {
          margin: 20px auto;
        }
      }
      .student_plan_right {
        display: flex;
        img {
          margin: 0 auto;
          width: 60%;
          height: auto;
        }
      }
    }
  }

  //  TV4K & AirPlay
  .lower_container {
    max-width: 1360px;
    margin: 40px auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    // TV4K
    .tv_4k {
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 48.5%;
      height: 100%;
      background-color: #f5f5f7;
      .violator-frameless {
        color: #bf4800;
        font-size: 17px;
        margin: 80px 0 10px;
      }
      .apple_tv_4k {
        width: 116px;
        height: 35px;
      }
      .headline {
        font-size: clamp(30px, 4vw, 48px);
        line-height: 1.0834933333;
        font-weight: 700;
        letter-spacing: -0.003em;
        color: #1d1d1f;
        text-align: center;
        margin-top: 21px;
        margin-bottom: 17px;
      }
      .typography_container {
        display: flex;
        align-items: center;
        padding-bottom: 100px;
        .button {
          margin: 0 0.8em;
          font-size: 17px;
          line-height: 1.1764805882;
          font-weight: 400;
          letter-spacing: -0.022em;
          min-width: 26px;
          padding: 12px 22px;
          border-radius: 980px;
          background: #0071e3;
          color: #fff;
        }
        .learn_more {
          color: #06c;
          font-size: 19px;
          line-height: 1.2105263158;
          font-weight: 400;
        }
      }
      .tv4k_img {
        width: 100%;
      }
    }
    // AirPlay
    .airplay {
      text-align: center;
      width: 48.5%;
      background-color: #f5f5f7;
      .eyebrow {
        margin-top: 110px;
        font-size: 32px;
        line-height: 1.125;
        font-weight: 600;
        letter-spacing: 0.004em;
      }
      .headline {
        font-size: clamp(30px, 4vw, 48px);
        line-height: 1.0834933333;
        font-weight: 700;
        letter-spacing: -0.003em;
        margin-top: 15px;
        margin-bottom: 36px;
      }
      .learn_more_container {
        display: flex;
        align-items: center;
        width: 110px;
        margin: 0 auto 100px;
        .learn_more {
          color: #06c;
          font-size: 19px;
          line-height: 1.2105263158;
          font-weight: 400;
        }
      }
      .airplay_img {
        width: 100%;
      }
    }
  }

  @media (min-width: 750px) and (max-width: 1000px) {
    .student_plan_container {
      height: 430px;
    }
  }
  @media (min-width: 599px) and (max-width: 750px) {
    .student_plan_container {
      height: 330px;
    }
  }
  @media (max-width: 750px) {
    .tv_4k {
      width: 100% !important;
      .typography_container {
        padding-bottom: 20px !important;
      }
      .tv4k_img {
        width: 80% !important;
      }
    }
    .airplay {
      width: 100% !important;
      .learn_more_container {
        margin: 0 auto 20px !important;
      }
      .airplay_img {
        width: 80% !important;
      }
    }
  }
}
</style>
