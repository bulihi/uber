<template>
  <div class="app">
    <div id="root">
      <div id="wrapper" class="ae af">
        <div class="ag ah ai aj"></div>
        <div data-testid="header-main" class="ae ak al am an ao ap">
          <svg xmlns="http://www.w3.org/2000/svg" width="57" height="20" fill="none">
            <path fill="#FFF"
                  d="M8 17.4c2.6 0 4.7-2 4.7-5.1V.3h2.9v19.4h-2.9v-1.8a7 7 0 01-5 2.1c-4.2 0-7.4-3-7.4-7.6V.4h3v11.9c0 3 2 5.1 4.6 5.1zM17.7.3h2.8v7a7 7 0 015-2c4 0 7.3 3.3 7.3 7.4 0 4-3.2 7.3-7.4 7.3a7 7 0 01-5-2.1v1.8h-2.7V.3zm7.6 17.2c2.6 0 4.8-2.1 4.8-4.9 0-2.7-2.2-4.8-4.8-4.8a4.8 4.8 0 00-4.9 4.8c0 2.8 2.2 5 4.9 5zM41.1 5.3c4 0 7 3.1 7 7.3v1H36.7c.4 2.2 2.3 4 4.7 4 1.6 0 3-.7 4-2.1l2 1.5a7.3 7.3 0 01-6 3 7.3 7.3 0 01-7.5-7.4c0-4 3.1-7.3 7.2-7.3zm-4.3 6h8.5a4.4 4.4 0 00-4.2-3.6c-2.1 0-3.8 1.5-4.3 3.6zM55.6 8c-1.8 0-3.2 1.5-3.2 3.7v8h-2.7V5.6h2.7v1.7a3.7 3.7 0 013.4-1.8h1V8h-1.2z"></path>
          </svg>
        </div>
        <div class="aq ar as at">
          <div class="ae au av aw ax as ay">
            <div role="main" screen-test="PHONE_NUMBER_INITIAL" flow-test="INITIAL" class="ae aq af ag az au b0">
              <div class="av ae af ao b1 ag">
                <div class="ae af b2"><h1 id="title" class="b3 b4 b5 b6 b7 b8 b9">What's your phone number?</h1>
                  <div class="ba"></div>
                  <div class="ae af bb">
                    <div class="">
                      <bdi class="ae bc ak bd">
                        <div id="PHONE_COUNTRY_CODE" data-testid="PHONE_COUNTRY_CODE" aria-label="Choose a country code"
                             class="be bf bg">
                          <div class="bh ae bi bj bk bl bm ao">
                            <div class="bn bo">
                              <div class="bp"><span class="bq br">🇭🇰</span></div>
                            </div>
                            <div class="ae ak">
                              <svg height="16" width="16" viewBox="0 0 24 24">
                                <path
                                    d="M12.7071 15.2929L17.1464 10.8536C17.4614 10.5386 17.2383 10 16.7929 10L7.20711 10C6.76165 10 6.53857 10.5386 6.85355 10.8536L11.2929 15.2929C11.6834 15.6834 12.3166 15.6834 12.7071 15.2929Z"></path>
                              </svg>
                            </div>
                          </div>
                        </div>
                        <div id="phone-number-or-email-input-container" class="ae bc bl bs bk au bm bt bu">
                          <div class="bv au"><input id="PHONE_NUMBER_or_EMAIL_ADDRESS"
                                                    title="Enter phone number" autocomplete="email webauthn"
                                                    inputmode="email" name="email" type="email" autocorrect="off"
                                                    autocapitalize="off" spellcheck="false" autofocus=""
                                                    placeholder="Enter phone number"
                                                    aria-label="Enter phone number"
                                                    class="bw bx by bd bz c0 bk au c1 c2 c3" value=""></div>
                        </div>
                      </bdi>
                    </div>
                    <p id="field-error" class="c4 c5 c6 b8 c7 bg"></p>
                    <p class="c4 c5 c6 b8 c7"></p>
                    <div class="c8"></div>
                    <button class="ew ex by d9 ae bx ak bh da bw db dc c0 dd de df bm dg dh ey ez" id="forward-button"
                            type="submit" data-testid="forward-button">
                      <div class="ae ao ak au">
                        <div class="ae ak"></div>
                        <div class="ae ak">Continue</div>
                        <div class="ae ak"></div>
                      </div>
                    </button>
                    <div>
                      <div class="c8"></div>
                      <div class="ae af ck ">
                        <div class="ae ak cl cm cn co cp cq cr cs ct cu cv cw"><p class="cx c5 cy">or</p></div>
                        <div class="ae af ck ">
                          <div class="uwa-capture">
                            <div class="d1 au">
                              <button class="d7 d8 by d9 ae bx ak bh da bw db dc c0 dd de df bm dg dh di dj au"
                                      my-attr="this-attr" id="google-login-btn" data-testid="google"
                                      data-tracking-name="social">
                                <div class="ae ao ak au">
                                  <div class="ae ak"></div>
                                  <div class="ae ak">
                                    <div class="ae ak aw">
                                      <div class="ae ak be">
                                        <svg width="18" height="18" viewBox="0 0 256 262"
                                             xmlns="http://www.w3.org/2000/svg" class="cz d0"
                                             preserveAspectRatio="xMidYMid">
                                          <path
                                              d="M255.9 133.5c0-10.8-.9-18.6-2.8-26.7H130.6v48.4h71.9a63.8 63.8 0 01-26.7 42.4l-.2 1.6 38.7 30 2.7.3c24.7-22.8 38.9-56.3 38.9-96"
                                              fill="#4285F4"></path>
                                          <path
                                              d="M130.6 261.1c35.2 0 64.8-11.6 86.4-31.6l-41.2-32c-11 7.8-25.8 13.1-45.2 13.1a78.6 78.6 0 01-74.3-54.2l-1.5.1-40.3 31.2-.6 1.5C35.4 231.8 79.5 261 130.6 261"
                                              fill="#34A853"></path>
                                          <path
                                              d="M56.3 156.4a80.4 80.4 0 01-.2-51.7V103L15.3 71.3l-1.4.6a130.7 130.7 0 000 117.3l42.4-32.8"
                                              fill="#FBBC05"></path>
                                          <path
                                              d="M130.6 50.5c24.5 0 41 10.6 50.4 19.4L218 34C195.2 13 165.8 0 130.6 0 79.5 0 35.4 29.3 13.9 72l42.2 32.7a79 79 0 0174.4-54.2"
                                              fill="#EB4335"></path>
                                        </svg>
                                      </div>
                                      <div class="ae af d3 d4"><p class="dl d9 b8">Continue with Google</p></div>
                                    </div>
                                  </div>
                                  <div class="ae ak"></div>
                                </div>
                              </button>
                            </div>
                          </div>
                          <div class="uwa-capture">
                            <div class="d1 au">
                              <button class="d7 d8 by d9 ae bx ak bh da bw db dc c0 dd de df bm dg dh di dj au"
                                      my-attr="this-attr" id="apple-login-btn" data-testid="apple"
                                      data-tracking-name="social">
                                <div class="ae ao ak au">
                                  <div class="ae ak"></div>
                                  <div class="ae ak">
                                    <div class="ae ak aw">
                                      <div class="ae ak be">
                                        <svg width="22" height="22" viewBox="0 0 22 22" fill="#000000"
                                             xmlns="http://www.w3.org/2000/svg" class="cz d0">
                                          <g transform="matrix( 1 0 0 1 3 1 )">
                                            <path fill-rule="evenodd" clip-rule="evenodd"
                                                  d="M11.2676 3.23104C11.9166 2.39314 12.4087 1.20886 12.2307 0C11.1698 0.0737252 9.92984 0.752465 9.2063 1.63717C8.54675 2.43878 8.00468 3.63126 8.21639 4.78863C9.37613 4.8249 10.5731 4.12978 11.2676 3.23104ZM17 14.6022C16.5359 15.6367 16.3125 16.099 15.7146 17.0153C14.8806 18.2943 13.7046 19.887 12.2459 19.8987C10.9512 19.9128 10.6173 19.0503 8.85967 19.0608C7.10203 19.0702 6.73561 19.9151 5.4386 19.9022C3.98106 19.8894 2.86668 18.4523 2.03264 17.1732C-0.300809 13.5993 -0.546251 9.404 0.892672 7.17235C1.91632 5.58785 3.53089 4.66101 5.04775 4.66101C6.59136 4.66101 7.56267 5.51295 8.84106 5.51295C10.0811 5.51295 10.836 4.65867 12.6216 4.65867C13.9733 4.65867 15.4052 5.39944 16.4242 6.67734C13.0834 8.5193 13.6243 13.3185 17 14.6022Z"
                                                  fill="#000000" opacity="1"></path>
                                          </g>
                                        </svg>
                                      </div>
                                      <div class="ae af d3 d4"><p class="dl d9 b8">Continue with Apple</p></div>
                                    </div>
                                  </div>
                                  <div class="ae ak"></div>
                                </div>
                              </button>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="c8"></div>
                    </div>
                    <div class="dm"></div>
                    <p id="formFooterPhone" data-testid="phone-footer" class="dn d9 b8 do bj dp">By proceeding, you
                      consent to get calls, WhatsApp or SMS/RCS messages, including by automated means, from Uber and
                      its affiliates to the number provided.</p></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="ae dq dr ds dt ak du af dv"></div>
        <div aria-hidden="true" class="full_screen_overlay dq bg au av dr ds dt dw dx dy"></div>
        <div id="loading_component" data-testid="loading_component"
             class="loading_component bg av aw ak ca ah au dz e0">
          <div data-testid="spinner" class="spinner cb cc cd ce cf cg ch ci cj"></div>
        </div>
      </div>
      <div class="">
        <div>
          <div data-focus-guard="true" tabindex="0"
               style="width: 1px; height: 0px; padding: 0px; overflow: hidden; position: fixed; top: 1px; left: 1px;"></div>
          <div data-focus-lock-disabled="false">
            <div data-baseweb="modal" data-testid="arkose-modal-closed" class="dq e1 dt dw dr ds e2 bg">
              <div class="ae e3 aw au e4 e5 e2 e6 e7 f0 e9 ea eb">
                <div tabindex="-1" aria-modal="true" aria-label="dialog" role="dialog"
                     class="d1 ec ed ee ef eg eh ei ej ek el au f0 f1 en ea eb eo ep eq er es et eu">
                  <div id="bottom-modal-content" class="ev">
                    <div
                        style="position: absolute; z-index: -1; top: 0px; left: 0px; height: 0px; width: 0px; overflow: hidden;">
                      <div id="arkose-challenge" tabindex="-1" style="outline: none;">
                        <div aria-hidden="false" class="arkose-30000F36-CADF-490C-929A-C6A7DD8B33C4-wrapper">
                          <iframe title="Verification challenge" aria-label="Verification challenge"
                                  src="https://uber-api.arkoselabs.com/v2/3.5.0/enforcement.df45d93b7883fed1e47dedac58c1d924.html#30000F36-CADF-490C-929A-C6A7DD8B33C4&amp;5af9cbb1-206c-4219-ba2d-21fc48c1539e"
                                  data-e2e="enforcement-frame"
                                  style="border: 0px; margin: 0px; padding: 0px; visibility: visible; opacity: 1; overflow: visible; display: block; transition: opacity 300ms linear; height: 100vh; z-index: 2147483647; width: 100vw; pointer-events: inherit; min-width: 300px; min-height: 250px; max-width: 400px; max-height: 450px;"></iframe>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div data-focus-guard="true" tabindex="0"
               style="width: 1px; height: 0px; padding: 0px; overflow: hidden; position: fixed; top: 1px; left: 1px;"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  name: 'App',
  setup() {
    const phoneNumber = ref('')
    const selectedCountry = ref('+1')
    const isLoading = ref(false)
    const isInputFocused = ref(false)

    const handleSubmit = async () => {
      if (!phoneNumber.value.trim()) return

      isLoading.value = true

      // Simulate API call
      try {
        await new Promise(resolve => setTimeout(resolve, 2000))
        alert('This is a demo. In real Uber, you would receive an SMS code.')
      } finally {
        isLoading.value = false
      }
    }

    const handleSocialLogin = (provider) => {
      alert(`Social login with ${provider} - This is a demo`)
    }

    return {
      phoneNumber,
      selectedCountry,
      isLoading,
      isInputFocused,
      handleSubmit,
      handleSocialLogin
    }
  }
}
</script>

<style>
body {
  display: block;
  margin: 0 !important;
}
</style>
<style scoped>
html, body, #root, #wrapper {
  height: 100%;
  width: 100%;

}

.af {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  flex-direction: column;
}
.bd {
  line-height: 24px;
}
.ao {
  -webkit-box-pack: justify;
  justify-content: space-between;
}
.an {
  background-color: #000000;
}
.am {
  padding: 0px 32px;
}
.al {
  min-height: 64px;
}
.ak {
  -webkit-box-align: center;
  align-items: center;
}
.ae {
  display: -webkit-box;
  display: -moz-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
}
*, *:before, *:after {
  box-sizing: inherit;
  font-family: -apple-system, BlinkMacSystemFont, "SegoeUI", Roboto, Helvetica, Arial, sans-serif, "AppleColorEmoji", "SegoeUIEmoji", "SegoeUISymbol";
}
user agent stylesheet
div {
  display: block;
  unicode-bidi: isolate;
}
*, *:before, *:after {
  box-sizing: inherit;
  font-family: -apple-system, BlinkMacSystemFont, "SegoeUI", Roboto, Helvetica, Arial, sans-serif, "AppleColorEmoji", "SegoeUIEmoji", "SegoeUISymbol";
}
*, *:before, *:after {
  box-sizing: inherit;
  font-family: -apple-system, BlinkMacSystemFont, "SegoeUI", Roboto, Helvetica, Arial, sans-serif, "AppleColorEmoji", "SegoeUIEmoji", "SegoeUISymbol";
}
svg[Attributes Style] {
  width: 57px;
  height: 20px;
  fill: none;
}
.aj {
  left: -10000px;
}

.ai {
  top: -10000px;
}
.ah {
  position: absolute;
}
.ag {
  box-sizing: border-box;
}
.aq {
  flex: 1;
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 0%;
}
.dv {
  padding-top: 12px;
}

.du {
  -webkit-box-pack: start;
  justify-content: flex-start;
}
.dt {
  right: 0;
}
.ds {
  left: 0;
}
.dr {
  top: 0;
}
.dq {
  position: fixed;
}
.ak {
  -webkit-box-align: center;
  align-items: center;
}
.af {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  flex-direction: column;
}
.dy {
  z-index: 2;
}

.dx {
  background-color: rgba(0, 0, 0, 0.5);
}
.dw {
  bottom: 0;
}
.dt {
  right: 0;
}
.ds {
  left: 0;
}
.dr {
  top: 0;
}
.dq {
  position: fixed;
}
.bg {
  display: none;
}
.av {
  height: 100%;
}
.au {
  width: 100%;
}
.e0 {
  opacity: 0.7;
}

.dz {
  background-color: #fff;
}
.ca {
  z-index: 100;
}
.bg {
  display: none;
}
.aw {
  -webkit-box-pack: center;
  justify-content: center;
}
.av {
  height: 100%;
}
.au {
  width: 100%;
}
.ak {
  -webkit-box-align: center;
  align-items: center;
}
.ah {
  position: absolute;
}
.cj {
  animation-iteration-count: infinite;
}
.ci {
  animation-timing-function: linear;
}
.ch {
  animation-duration: 1s;
}
.cg {
  animation-name: ae;
}
.cf {
  height: 40px;
}
.ce {
  width: 40px;
}
.cd {
  border-top: 6px solid #276EF1;
}
.cc {
  border-radius: 50%;
}
.cb {
  border: 6px solid #F3F3F3;
}
.b9 {
  color: #000000;
}

.b8 {
  margin: 0px;
}
.b5 {
  line-height: 32px;
}
.b4 {
  font-weight: 400;
}
.b3 {
  font-size: 20px;
}
.ba {
  height: 8px;
}
.bb {
  flex: 1 0 auto;
}
.bg {
  display: none;
}

.bf {
  min-width: 104px;
}
.be {
  margin-right: 8px;
}
.bm {
  border-radius: 8px;
}
.bl {
  border: 2px solid transparent;
}
.bk {
  background: #eee;
}
.bj {
  padding-right: 16px;
}
.bi {
  padding-left: 6px;
}
.bh {
  cursor: pointer;
}
.ao {
  -webkit-box-pack: justify;
  justify-content: space-between;
}
.bo {
  padding: 10px 0 10px 10px;
}

.bn {
  font-size: 32px;
}
.br {
  display: inherit;
}
.bq {
  margin-right: 10px;
}
.bs {
  padding: 10px 0 10px 12px;
}

.bm {
  border-radius: 8px;
}
.bl {
  border: 2px solid transparent;
}
.bk {
  background: #eee;
}
.bc {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  flex-direction: row;
}
.bv {
  padding-left: 4px;
}
.c7 {
  padding-top: 0px;
}

.c6 {
  color: #E54937;
}
.c5 {
  line-height: 16px;
}
.c4 {
  font-size: 13px;
}
.c2 {
  padding-right: unset;
}

.c1 {
  text-align: left;
}
.c0 {
  margin: 0;
}
.bz {
  padding: 0;
}
.by {
  font-size: 16px;
}
.bx {
  border: none;
}
.bw {
  outline: none;
}
.bk {
  background: #eee;
}
.bd {
  line-height: 24px;
}
.ex {
  color: rgb(255, 255, 255);
}
.ew {
  background: rgb(0, 0, 0);
}
.dh {
  min-height: 48px;
}
.dg {
  padding: 14px 16px;
}
.dc {
  font-weight: 500;
}
.db {
  box-shadow: none;
}
.da {
  -webkit-transition: background 200ms cubic-bezier(0, 0, 1, 1);
  -moz-transition: background 200ms cubic-bezier(0, 0, 1, 1);
  transition: background 200ms cubic-bezier(0, 0, 1, 1);
}
.d9 {
  line-height: 20px;
}
.c0 {
  margin: 0;
}
.by {
  font-size: 16px;
}
.bx {
  border: none;
}
.bw {
  outline: none;
}
.bm {
  border-radius: 8px;
}
.bh {
  cursor: pointer;
}
.c8 {
  height: 16px;
}
.ck {
  gap: 8px;
}
.cm {
  padding: 4px 0;
}

.cl {
  color: #AFAFAF;
}
.cy {
  margin: 0 8px;
}

.cx {
  font-size: 14px;
}
.c5 {
  line-height: 16px;
}
.cr::before {
  -webkit-box-flex: 1;
  flex-grow: 1;
}

.cq::before {
  height: 1px;
}
.cp::before {
  background: #AFAFAF;
}
.co::before {
  display: block;
}
.cn::before {
  content: " ";
}
*, *:before, *:after {
  box-sizing: inherit;
  font-family: -apple-system, BlinkMacSystemFont, "SegoeUI", Roboto, Helvetica, Arial, sans-serif, "AppleColorEmoji", "SegoeUIEmoji", "SegoeUISymbol";
}
.cw::after {
  -webkit-box-flex: 1;
  flex-grow: 1;
}
.cv::after {
  height: 1px;
}
.cu::after {
  background: #AFAFAF;
}
.ct::after {
  display: block;
}
.cs::after {
  content: " ";
}
p {
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  unicode-bidi: isolate;
}
.d1 {
  position: relative;
}
.dh {
  min-height: 48px;
}
.dg {
  padding: 14px 16px;
}
.dc {
  font-weight: 500;
}
.db {
  box-shadow: none;
}
.da {
  -webkit-transition: background 200ms cubic-bezier(0, 0, 1, 1);
  -moz-transition: background 200ms cubic-bezier(0, 0, 1, 1);
  transition: background 200ms cubic-bezier(0, 0, 1, 1);
}
.d9 {
  line-height: 20px;
}
.d8 {
  color: black;
}
.d7 {
  background: #E8E8E8;
}
.c0 {
  margin: 0;
}
.by {
  font-size: 16px;
}
.bx {
  border: none;
}
.bw {
  outline: none;
}
.bm {
  border-radius: 8px;
}
.bh {
  cursor: pointer;
}
button {
  margin: 0;
  padding: 0;
  border: none;
  background: none;
  outline: none;
}

.dc {
  font-weight: 500;
}
.d9 {
  line-height: 20px;
}
.d8 {
  color: black;
}
.by {
  font-size: 16px;
}
.bh {
  cursor: pointer;
}
.d4 {
  text-align: center;
}
.d3 {
  -webkit-box-align: start;
  align-items: start;
}
.dm {
  margin-bottom: 24px;
}
.dp {
  margin-bottom: 8px;
}

.do {
  color: #6B6B6B;
}
.dn {
  font-size: 12px;
}
.d9 {
  line-height: 20px;
}
.bj {
  padding-right: 16px;
}
.b8 {
  margin: 0px;
}
.dv {
  padding-top: 12px;
}
.b1 {
  padding-top: 16px;
}
.az {
  padding: 0 16px;
}
.du {
  -webkit-box-pack: start;
  justify-content: flex-start;
}
.dt {
  right: 0;
}
.ds {
  left: 0;
}
.dr {
  top: 0;
}
.dq {
  position: fixed;
}


</style>