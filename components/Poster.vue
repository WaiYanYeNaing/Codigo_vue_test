<template>
  <div class="poster_main_container">
    <div class="poster">
      <div class="overlay">
        <div class="title">
          All Apple Originals.<br />
          Only on Apple TV+.
        </div>
        <div class="stream_now">
          <NuxtLink to="/TvApple" style="text-decoration: none"
            >Stream now</NuxtLink
          >
        </div>
        <div class="watch">
          Watch on the
          <img
            src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/hero_icon__gpaz9xyhw0uq_large.png"
            alt=""
            style="margin: 0 6px"
          />
          app
        </div>
      </div>
      <img
        class="poster_img"
        src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/hero_startframe__fs1yactuf3qm_large.jpg"
        alt=""
      />
    </div>
  </div>
</template>

<style lang="scss">
.poster_main_container {
  .poster {
    height: 100vh;
    .overlay {
      position: absolute;
      bottom: 43px;
      left: 20px;
      width: 90%;
      .title {
        font-size: clamp(40px, 6vw, 80px);
        line-height: 1.05;
        font-weight: 700;
        letter-spacing: -0.015em;
        color: #f5f5f7;
      }
      .stream_now {
        background-color: #fff;
        font-weight: 600;
        margin-top: 25px;
        cursor: pointer;
        display: inline-block;
        text-align: center;
        white-space: nowrap;
        padding: 18px 31px;
        font-size: 17px;
        line-height: 1.1764805882;
        letter-spacing: -0.022em;
        border-radius: 980px;
      }
      .watch {
        margin-top: 52px;
        color: #fff;
        display: flex;
        align-items: center;
        font-size: 19px;
        line-height: 1.2105263158;
        letter-spacing: 0.012em;
      }
    }
    .poster_img {
      width: 100%;
      height: 100vh;
      object-fit: cover;
    }
  }
}
</style>
