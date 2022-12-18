<template>
  <div class="footer_main_container">
    <!-- Foot Notes -->
    <div class="foot_notes_container">
      <div>
        <div class="foot_notes">* MLS Season Pass requires a subscription.</div>
        <div class="foot_notes">
          1. $6.99/month after free trial. Only one offer per Apple ID and only
          one offer per family if you’re part of a Family Sharing group,
          regardless of the number of devices you or your family purchases. This
          offer is not available if you or your Family have previously accepted
          an Apple TV+ one year free offer. Offer good for 3 months after
          eligible device activation. Plan automatically renews until cancelled.
          Restrictions and other terms apply.
        </div>
        <div class="foot_notes">
          2. One subscription per Family Sharing group. Plan automatically
          renews until cancelled.
        </div>
        <div class="foot_notes">
          3. The Apple One free trial includes only services that you are not
          currently using through a free trial or a subscription. Plan
          automatically renews after trial until cancelled. Restrictions and
          other terms apply.
        </div>
        <div class="foot_notes">
          4. Limited-time offer; offer may end at any time. Free Apple TV+
          access for students ends when you no longer qualify or do not renew
          your Apple Music Student subscription. Offer good for verified college
          students only and does not extend to a Family Sharing group.
        </div>
      </div>
    </div>

    <!-- Breadcrumbs -->
    <div class="breadcrumbs_container">
      <div class="breadcrumbs">
        <div>
          <img src="https://img.icons8.com/ios-glyphs/16/null/mac-os.png" />
        </div>
        <div>
          <img
            src="https://img.icons8.com/material-sharp/15/424245/chevron-right.png"
          />
        </div>
        <div>Only on Apple</div>
        <div>
          <img
            src="https://img.icons8.com/material-sharp/15/424245/chevron-right.png"
          />
        </div>
        <div>Apple TV+</div>
      </div>
    </div>

    <!-- Apple Directory -->
    <div class="apple_directory_container" v-show="!$vuetify.breakpoint.xs">
      <v-row>
        <v-col cols="12" lg="2" md="3" sm="4">
          <div class="apple_title">Shop and Learn</div>
          <div>Store</div>
          <div>Mac</div>
          <div>iPad</div>
          <div>iPhone</div>
          <div>Watch</div>
          <div>AirPods</div>
          <div>TV & Home</div>
          <div>AirTag</div>
          <div>Accessories</div>
          <div>Gift Cards</div>
        </v-col>
        <v-col cols="12" lg="2" md="3" sm="4">
          <div class="apple_title">Services</div>
          <div>Apple Music</div>
          <div>Apple TV+</div>
          <div>Apple Fitness+</div>
          <div>Apple News+</div>
          <div>Apple Arcade</div>
          <div>iCloud</div>
          <div>Apple One</div>
          <div>Apple Card</div>
          <div>Apple Books</div>
          <div>Apple Podcasts</div>
          <div>App Store</div>
          <div class="apple_title" style="padding-top: 24px">Account</div>
          <div>Manage Your Apple ID</div>
          <div>Apple Store Account</div>
          <div>iCloud.com</div>
        </v-col>
        <v-col cols="12" lg="2" md="3" sm="4">
          <div class="apple_title">Apple Store</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
        </v-col>
        <v-col cols="12" lg="2" md="3" sm="4">
          <div class="apple_title">For Business</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div class="apple_title" style="padding-top: 24px">For Education</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div class="apple_title" style="padding-top: 24px">
            For Healthcare
          </div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div class="apple_title" style="padding-top: 24px">
            For Government
          </div>
          <div>xaxax</div>
          <div>xaxax</div>
        </v-col>
        <v-col cols="12" lg="2" md="3" sm="4">
          <div class="apple_title">Apple Values</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div class="apple_title" style="padding-top: 24px">About Apple</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
          <div>xaxax</div>
        </v-col>
      </v-row>
    </div>

    <div class="apple_directory_container" v-show="$vuetify.breakpoint.xs">
      <div class="section_title" v-for="(item, i) in apple_items" :key="i">
        <span>{{ item.title }}</span>
        <img
          src="https://img.icons8.com/external-tanah-basah-detailed-outline-tanah-basah/15/424245/external-plus-user-interface-tanah-basah-detailed-outline-tanah-basah-2.png"
        />
      </div>
    </div>

    <!-- Footer -->
    <div class="footer_container">
      <div class="footer_shop">
        More ways to shop:
        <span class="link">Find an Apple Store</span> or
        <span class="link"> other retailer</span> near you. Or call
        1-800-MY-APPLE.
      </div>
      <div class="footer_legal">
        <div class="legal_link">
          Copyright © 2022 Apple Inc. All rights reserved.
        </div>
        <div class="copyright border_r">Privacy Policy</div>
        <div class="legal_link border_r">Terms of Use</div>
        <div class="legal_link border_r">Sales and Refunds</div>
        <div class="legal_link border_r">Legal</div>
        <div class="legal_link">Site Map</div>
        <v-spacer />
        <div>United States</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    apple_items: [
      {
        title: 'Shop and Learn',
        isShow: false,
      },
      {
        title: 'Services',
        isShow: false,
      },
      {
        title: 'Account',
        isShow: false,
      },
      {
        title: 'Apple Store',
        isShow: false,
      },
      {
        title: 'For Business',
        isShow: false,
      },
      {
        title: 'For Education',
        isShow: false,
      },
      {
        title: 'For Healthcare',
        isShow: false,
      },
      {
        title: 'For Government',
        isShow: false,
      },
      {
        title: 'Apple Values',
        isShow: false,
      },
      {
        title: 'About Apple',
        isShow: false,
      },
    ],
  }),
}
</script>

<style lang="scss">
@import '~assets/variables';
.footer_main_container {
  font-family: 'SF Pro';
  font-size: 12px;
  background-color: #f5f5f7;

  //   Foot Notes
  .foot_notes_container {
    padding: 17px 22px 11px;
    max-width: 980px;
    margin: 0 auto;
    .foot_notes {
      color: #6e6e73;
      line-height: 1.33337;
      font-weight: 400;
      letter-spacing: -0.01em;
      padding-bottom: 0.8em;
    }
    border-bottom: 1px solid $footer-border-color;
  }

  //   Breadcrumbs
  .breadcrumbs_container {
    max-width: 980px;
    padding: 17px 22px;
    margin: 0 auto;
    color: #424245;
    .breadcrumbs {
      display: flex;
      justify-content: space-between;
      max-width: 200px;
      height: 15px;
    }
  }

  //   Apple Directory
  .apple_directory_container {
    max-width: 980px;
    padding: 0 22px;
    margin: 0 auto;
    color: #424245;
    div {
      justify-content: space-between;
      div {
        margin-bottom: 0.8em;
        cursor: pointer;
        .apple_title {
          color: #1d1d1f;
          font-weight: 600;
          cursor: default;
        }
      }
    }
    .section_title {
      border-bottom: 1px solid #d2d2d7;
      padding: 10px 0;
      display: flex;
      align-items: center;
    }
  }

  //   Footer
  .footer_container {
    color: #6e6e73;
    padding: 34px 22px;
    max-width: 980px;
    margin: 0 auto;
    .footer_shop {
      margin-bottom: 7px;
      padding-bottom: 8px;
      border-bottom: 1px solid #d2d2d7;
      .link {
        color: #0066cc;
      }
    }
    .footer_legal {
      display: flex;
      flex-wrap: wrap;
      line-height: 20px;
      .copyright {
        padding-right: 0.7rem;
      }
      .legal_link {
        padding-right: 0.7rem;
        margin-right: 0.7rem;
      }
      .border_r {
        border-right: 1px solid #d2d2d7;
      }
    }
  }
}
</style>
