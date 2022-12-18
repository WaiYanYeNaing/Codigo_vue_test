<template>
  <div class="navbar_main_container">
    <div class="nav">
      <img
        src="https://www.apple.com/ac/globalnav/7/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_apple_image__b5er5ngrzxqq_large.svg"
      />
      <div>Store</div>
      <div>Mac</div>
      <div>iPad</div>
      <div>iPhone</div>
      <div>Watch</div>
      <div>AirPods</div>
      <div>TV & Home</div>
      <div>Only on Apple</div>
      <div>Accessories</div>
      <div>Support</div>
      <img
        style="width: 17px; height: 17px"
        src="https://img.icons8.com/external-kiranshastry-lineal-kiranshastry/260/f5f5f7/external-search-logistic-delivery-kiranshastry-lineal-kiranshastry.png"
      />
      <img
        src="https://www.apple.com/ac/globalnav/7/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_bag_image__yzte50i47ciu_large.svg"
        alt=""
      />
    </div>
    <div class="mobile_nav">
      <img src="https://img.icons8.com/windows/18/f5f5f7/menu--v1.png" />
      <img
        src="https://www.apple.com/ac/globalnav/7/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_apple_image__b5er5ngrzxqq_large.svg"
      />
      <img
        src="https://www.apple.com/ac/globalnav/7/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_bag_image__yzte50i47ciu_large.svg"
        alt=""
      />
    </div>
    <div class="sticky_nav">
      <span class="apple_tv">Apple TV+</span>
      <div class="stream">
        <NuxtLink to="/TvApple" style="text-decoration: none"
          >Stream now</NuxtLink
        >
      </div>
    </div>
    <div class="notify">
      <div>
        MLS Season Pass. Stream every Major League Soccer match. Coming soon.*
        <span
          ><NuxtLink to="/TvApple" style="text-decoration: none"
            >&nbsp;Notify me</NuxtLink
          >
        </span>

        <img
          src="https://img.icons8.com/material-outlined/18/2997ff/forward.png"
        />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.navbar_main_container {
  background: #000000;
  .nav {
    font-size: 12px;
    line-height: 3.66667;
    font-weight: 400;
    letter-spacing: -0.01em;
    color: #f5f5f7;
    opacity: 0.8;
    padding: 0 22px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .mobile_nav {
    font-size: 12px;
    line-height: 3.66667;
    font-weight: 400;
    letter-spacing: -0.01em;
    color: #f5f5f7;
    opacity: 0.8;
    padding: 0 22px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .sticky_nav {
    background: #111;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 22px;
    .apple_tv {
      color: #fff;
      font-size: clamp(19px, 3vw, 21px);
      line-height: 1.14286;
      font-weight: 600;
      letter-spacing: 0.011em;
      cursor: default;
      display: block;
      float: left;
      margin: 14px 0 -14px;
      padding: 0;
      height: 52px;
    }
    .stream {
      font-weight: 400;
      background: linear-gradient(#ffffff, #e5e5e5);
      border-color: #fafafc;
      color: #1d1d1f;
      cursor: pointer;
      display: inline-block;
      text-align: center;
      white-space: nowrap;
      border-radius: 980px;
      font-size: 12px;
      line-height: 1.33337;
      letter-spacing: -0.01em;
      min-width: 23px;
      padding-left: 11px;
      padding-right: 11px;
      padding-top: 4px;
      padding-bottom: 4px;
    }
  }
  .notify {
    height: 52px;
    border-top: 1px solid rgba(255, 255, 255, 0.226);
    padding: 0 22px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: #111;
    color: white;
    div {
      span {
        color: #2997ff;
        cursor: pointer;
      }
      img {
        position: relative;
        top: 4px;
      }
    }
  }
  @media (min-width: 751px) {
    .mobile_nav {
      display: none;
    }
  }
  @media (max-width: 750px) {
    .nav {
      display: none;
    }
    .notify {
      font-size: 14px;
    }
  }
}
</style>
