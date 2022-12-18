<template>
  <div class="tv_app_main_container">
    <!-- Apple Logo -->
    <div class="apple_logo">
      <img
        src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/apple_tv_app_icon__cth1s5qlqpyu_xlarge.png"
        alt="apple_logo"
      />
    </div>
    <!-- Headline -->
    <div class="headline">
      Watch Apple TV+ anywhere <br />
      on the Apple TV app.
    </div>
    <!-- Typography -->
    <div class="typography">
      Find the Apple TV app on your favorite Apple devices.<br />
      Or watch Apple TV+ online at <span class="link">tv.apple.com.</span>
    </div>
    <!-- Buildin -->
    <div class="buildin">
      <div class="buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_apple_tv__r2nel0gcigam_large.jpg"
          alt="apple_tv"
        />
        <div class="device_name">Apple TV</div>
      </div>
      <div class="buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_iphone__c914mkstye0y_large.jpg"
          alt="iphone"
        />
        <div class="device_name">iPhone</div>
      </div>
      <div class="buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_ipad__cyk6qow5fiqa_large.jpg"
          alt="ipad"
        />
        <div class="device_name">iPad</div>
      </div>
      <div class="buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_mac__b7y797p7oouq_large.jpg"
          alt="mac"
        />
        <div class="device_name">Mac</div>
      </div>
      <div class="buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_airplay__ddkvcm0sxtm6_large.jpg"
          alt="airplay"
        />
        <div class="device_name">AirPlay</div>
      </div>
    </div>
    <!-- Sub Head -->
    <div class="sub_head">
      See it on your smart TV <br />
      or streaming device.
    </div>
    <div class="setup">
      <div>Set up your device</div>
      <img
        src="https://img.icons8.com/material-outlined/18/0f64ba/forward.png"
      />
    </div>
    <div class="explore">
      <div>Explore compatible devices</div>
      <img
        src="https://img.icons8.com/material-outlined/18/0f64ba/forward.png"
      />
    </div>
    <!-- External Buildin -->
    <div class="external_buildin">
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_samsung__er6s8sp9t126_large.jpg"
          alt="samsung"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_lg__7fxn3l0zf5ua_large.jpg"
          alt="lg"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_vizio__crgnno5ezt2e_large.jpg"
          alt="vizio"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_sony__dv28xq4n91ea_large.jpg"
          alt="sony"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_xfinity__fohor3dbqrmi_large.jpg"
          alt="xfinity"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_roku__d3kr4gpcimoi_large.jpg"
          alt="roku"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_firetv__f6qpefrj0ree_large.jpg"
          alt="firetv"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_google_tv__e5t4asdc2gsy_large.jpg"
          alt="googletv"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_playstation__djtq2b40wf2a_large.jpg"
          alt="ps"
        />
      </div>
      <div class="external_buildin_item">
        <img
          src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_xbox__cfelmbxxfoaa_large.jpg"
          alt="xbox"
        />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.tv_app_main_container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  width: 980px;
  margin: 0 auto;
  //   Apple Logo
  .apple_logo {
    width: 86px;
    height: 86px;
    margin: 130px auto 17px;
  }
  //   Headline
  .headline {
    font-size: clamp(30px, 5vw, 80px);
    line-height: 1.05;
    font-weight: 700;
    letter-spacing: -0.015em;
  }
  //   Typography
  .typography {
    margin-top: 20px;
    margin-bottom: 18px;
    font-size: 17px;
    line-height: 1.4705882353;
    font-weight: 400;
    letter-spacing: -0.022em;
    padding-bottom: 52px;
    .link {
      color: #0066cc;
      cursor: pointer;
    }
  }
  //   Buildin
  .buildin {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: 0px 20px 67px;
    width: 100%;
    .buildin_item {
      width: 78px;
      .device_name {
        font-size: 19px;
        line-height: 1.2105263158;
        letter-spacing: 0.012em;
        margin-top: 17px;
      }
    }
  }
  //   Sub head
  .sub_head {
    font-size: clamp(28px, 3.5vw, 40px);
    line-height: 1.1;
    font-weight: 600;
    letter-spacing: 0em;
  }
  .setup {
    display: flex;
    align-items: center;
    color: #06c;
    font-size: 17px;
    line-height: 1.4705882353;
    font-weight: 400;
    letter-spacing: -0.022em;
    margin-top: 0.8em;
  }
  .explore {
    display: flex;
    align-items: center;
    color: #06c;
    font-size: 17px;
    line-height: 1.4705882353;
    font-weight: 400;
    letter-spacing: -0.022em;
    margin-top: 0.4em;
  }
  //   Externl Buildin
  .external_buildin {
    display: flex;
    justify-content: space-between;
    margin-top: 38px;
    flex-wrap: wrap;
    text-align: center;
    .external_buildin_item {
      margin-bottom: 26px;
      padding: 0 30px;
    }
  }
  @media only screen and (max-width: 1000px) {
    .buildin {
      width: 80%;
    }
  }
  @media only screen and (max-width: 730px) {
    .buildin_item {
      flex-basis: 33%;
      margin-bottom: 30px;
    }
  }
}
@media only screen and (max-width: 1000px) {
  .tv_app_main_container {
    width: auto;
  }
}
</style>
