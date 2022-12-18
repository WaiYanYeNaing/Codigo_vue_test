<template>
  <div class="shows_main_container">
    <!-- Feature Shows Slider -->
    <div class="feature_shows_container">
      <div class="feature_show">
        <img
          src="https://is5-ssl.mzstatic.com/image/thumb/Features112/v4/60/52/a7/6052a7da-2a60-3756-4c4f-b907173e44d7/bbc79a26-1ae1-4406-aff1-fc2ffda59f40.png/1839x766sr.jpg"
          alt=""
        />
      </div>
      <div class="feature_show">
        <img
          src="https://is2-ssl.mzstatic.com/image/thumb/Features116/v4/7c/e4/64/7ce46417-ed07-323b-31f1-592a6d63cfa7/Q1NXLVRWQS1XVy1TUFRfRWFybHlDb21pbmdTb29uLnBuZw.png/1839x766sr.jpg"
          alt=""
        />
      </div>
      <div class="feature_show">
        <img
          src="https://is5-ssl.mzstatic.com/image/thumb/Features124/v4/bf/a6/2e/bfa62e08-e96a-3666-47ff-3307b36b4a90/Q1NXLVRWQS1XVy1CcmFuZF9QRUEtQy5wbmc.png/1839x766sr.jpg"
          alt=""
        />
      </div>
      <div class="feature_show">
        <img
          src="https://is5-ssl.mzstatic.com/image/thumb/Features122/v4/4b/06/a2/4b06a27a-2f1e-854d-acb3-db320855597f/a6d0e889-dfd7-4d84-aeac-cf46d1c364ad.png/735x1590.jpg"
          alt=""
        />
      </div>
      <div class="feature_show">SHows</div>
      <div class="feature_show">SHows</div>
    </div>
    <!-- Slider 1 -->
    <div class="slider_1_container">
      <img v-for="(movie, i) in movies" :key="i" :src="movie.url" alt="" />
    </div>
    <!-- Slider 2 -->
    <div class="slider_2_container">
      <img v-for="(movie, i) in movies" :key="i" :src="movie.url" alt="" />
    </div>
    <!-- See Full -->
    <div class="see_full_container">
      <div style="width: 80px" />
      <div class="see_full">
        See full lineup
        <img
          src="https://img.icons8.com/material-outlined/18/ffffff/forward.png"
        />
      </div>
      <img
        class="play_pause"
        src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/controls/pause_icon__dctqqxjvvpme_large.svg"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    movies: [
      {
        url: 'https://is3-ssl.mzstatic.com/image/thumb/pQ3h4ry4qTouWNP2zrc5MA/378x212.jpg',
      },
      {
        url: 'https://is1-ssl.mzstatic.com/image/thumb/gkWjLqLfF8Pahc6a6Udtxg/378x212.jpg',
      },
      {
        url: 'https://is5-ssl.mzstatic.com/image/thumb/RcgPZ5VHFSmr43fk1fjuMw/378x212.jpg',
      },
      {
        url: 'https://is1-ssl.mzstatic.com/image/thumb/Ogd5vHGYkYpUIzgQCTqBXQ/378x212.jpg',
      },
      {
        url: 'https://is2-ssl.mzstatic.com/image/thumb/HRBOk7ebJJpnufwvrhXLUw/378x212.jpg',
      },
      {
        url: 'https://is2-ssl.mzstatic.com/image/thumb/_vkF4kzNiSCdmWsVNp0gjw/378x212.jpg',
      },
      {
        url: 'https://is1-ssl.mzstatic.com/image/thumb/IyvoDdhWEjtSADaSryepIw/378x212.jpg',
      },
      {
        url: 'https://is3-ssl.mzstatic.com/image/thumb/neRAWaMZZ5xVz4fnbFXJUA/378x212.jpg',
      },
      {
        url: 'https://is4-ssl.mzstatic.com/image/thumb/q15eqXAa_XH-L0KIDkPBJA/378x212.jpg',
      },
      {
        url: 'https://is4-ssl.mzstatic.com/image/thumb/rbA884KpTpFowJZ9t08rhw/378x212.jpg',
      },
      {
        url: 'https://is3-ssl.mzstatic.com/image/thumb/d6sprLP3-1W-OlED4ZlzOg/378x212.jpg',
      },
      {
        url: 'https://is3-ssl.mzstatic.com/image/thumb/CXnyehPcDHEauavhg0D79Q/378x212.jpg',
      },
      {
        url: 'https://is1-ssl.mzstatic.com/image/thumb/r85VE266WcKhz9SdLwhb0A/378x212.jpg',
      },
      {
        url: 'https://is5-ssl.mzstatic.com/image/thumb/PWsYggMXgU6kQrxaB3MZPQ/378x212.jpg',
      },
      {
        url: 'https://is4-ssl.mzstatic.com/image/thumb/JMOPe5jKWbfZXlb8Z85rFg/378x212.jpg',
      },
    ],
  }),
}
</script>

<style lang="scss">
.shows_main_container {
  background: #000;
  //   Feature Shows Slider
  .feature_shows_container {
    height: auto;
    display: flex;
    margin-bottom: 15px;
    margin-left: -250px;
    overflow-x: hidden;
    .feature_show {
      img {
        width: 555px;
        height: 312px;
        object-fit: cover;
        margin: 0 7px;
        border-radius: 10px;
      }
    }
  }
  //   Slider 1
  .slider_1_container {
    margin: 0;
    padding: 0;
    white-space: nowrap;
    font-size: 0;
    overflow-x: hidden;
    img {
      width: 378px;
      height: 212px;
      border-radius: 10px;
      background-size: cover;
      display: inline-block;
      position: relative;
      margin: 0 10px 20px;
    }
  }
  //   Slider 2
  .slider_2_container {
    margin-left: -1000px;
    padding: 0;
    white-space: nowrap;
    font-size: 0;
    overflow-x: hidden;
    img {
      width: 378px;
      height: 212px;
      border-radius: 10px;
      background-size: cover;
      display: inline-block;
      position: relative;
      margin: 0 10px 20px;
    }
  }
  //   See Full
  .see_full_container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    .see_full {
      display: flex;
      max-width: 152px;
      justify-content: center;
      align-items: center;
      text-align: center;
      white-space: nowrap;
      border-radius: 980px;
      min-width: 26px;
      padding: 12px 22px;
      font-size: 14px;
      line-height: 1.4285914286;
      letter-spacing: -0.016em;
      font-weight: 700;
      cursor: pointer;
      background: none;
      border: 1px solid #fff;
      color: #fff;
      margin: 18px 0 50px;
    }
    .play_pause {
      cursor: pointer;
      width: 36px;
      height: 36px;
      margin: 18px 42px 50px 0;
    }
  }
  @media only screen and (max-width: 1070px) {
    .slider_1_container {
      img {
        width: 210px !important;
        height: 118px !important;
        margin: 0 7px 14px;
      }
    }
    .slider_2_container {
      img {
        width: 210px !important;
        height: 118px !important;
        margin: 0 7px 14px;
      }
    }
  }
  @media only screen and (max-width: 733px) {
    .feature_shows_container {
      .feature_show {
        img {
          width: 278px;
          height: 494px;
        }
      }
    }
  }
}
</style>
