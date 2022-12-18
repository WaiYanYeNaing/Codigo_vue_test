<template>
  <div class="offer_main_container">
    <!-- Content -->
    <div class="content">
      <div>New Apple Originals every month.</div>
      <div style="margin-top: 50px">
        Stream on the Apple TV app on Apple <br />
        devices, smart TVs, consoles, or sticks.
      </div>
      <div style="margin-top: 50px">Share Apple TV+ with your family.</div>
    </div>

    <!-- Plans -->
    <div class="plans_container">
      <div class="plan">
        <div class="eyebrow">Buy an Apple device</div>
        <div class="headline">3 months free.</div>
        <div class="typography">
          Apple TV+ is included for 3 months when you purchase an Apple device
          and redeem the offer within 90 days.
        </div>
        <div class="button">Check eligibility</div>
      </div>
      <div class="plan">
        <div class="eyebrow">Free 7-day trial</div>
        <div class="headline">$6.99/mo.</div>
        <div class="typography">
          A monthly subscription is just $6.99 per month after a free 7-day
          trial. Share Apple TV+ with your family.
        </div>
        <div class="button">Try if free</div>
      </div>
      <div class="plan">
        <div class="eyebrow">Free 1‑month trial</div>
        <div class="headline">Apple One</div>
        <div class="typography">
          Bundle Apple TV+ with up to five other great services for one low
          monthly price. And enjoy more for less. Learn more
        </div>
        <div class="button">Try Apple One free</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.offer_main_container {
  background: #000;
  color: #f5f5f7;
  font-size: 40px;
  line-height: 1.0834933333;
  font-weight: 700;
  letter-spacing: -0.003em;
  font-family: SF Pro Display, SF Pro Icons, Helvetica Neue, Helvetica, Arial,
    sans-serif;
  .content {
    margin-left: auto;
    margin-right: auto;
    padding-top: 100px;
    padding-bottom: 150px;
    max-width: 70%;
  }
  .plans_container {
    display: flex;
    flex-wrap: wrap;
    padding-bottom: 175px;
    margin-left: auto;
    margin-right: auto;
    max-width: 70%;
    .plan {
      flex-basis: 33.33%;
      max-width: 33.33%;
      .eyebrow {
        font-size: clamp(17px, 2vw, 21px);
        line-height: 1.1904761905;
        font-weight: 600;
        letter-spacing: 0.011em;
      }
      .headline {
        font-size: clamp(28px, 3.5vw, 40px);
        line-height: 1.1;
        font-weight: 700;
        letter-spacing: 0em;
        margin-top: 16px;
      }
      .typography {
        color: #a1a1a6;
        margin-top: 12px;
        margin-bottom: 25px;
        font-size: 17px;
        line-height: 1.4705882353;
        font-weight: 400;
        letter-spacing: -0.022em;
        padding-right: 40px;
      }
      .button {
        margin-top: 0;
        display: inline-block;
        text-align: center;
        white-space: nowrap;
        border-radius: 980px;
        padding: 12px 22px;
        font-size: 14px;
        line-height: 1.4285914286;
        letter-spacing: -0.016em;
        font-weight: 700;
        background-color: #fff;
        color: #1d1d1f;
        cursor: pointer;
        min-width: 110px;
      }
    }
  }
}

@media only screen and (max-width: 1068px) {
  .offer_main_container {
    font-size: 35px;
    line-height: 1.1;
    font-weight: 700;
    letter-spacing: 0em;
    .content {
      max-width: 85%;
    }
    .plans_container {
      max-width: 85%;
    }
  }
}

@media only screen and (max-width: 734px) {
  .offer_main_container {
    font-size: 28px;
    line-height: 1.2858342857;
    font-weight: 700;
    letter-spacing: 0.007em;
    .content {
      max-width: 90%;
    }
    .plans_container {
      max-width: 90%;
      .plan {
        flex-basis: 100% !important;
        max-width: 100% !important;
        margin-bottom: 60px;
      }
    }
  }
}
</style>
