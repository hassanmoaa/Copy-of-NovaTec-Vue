<template>
  <div id="Footer" class="footer1-footer">
    <div class="footer1-container1">
      <img :alt="imageAlt" :src="imageSrc" class="footer1-image1" />
      <div class="footer1-left">
        <div class="footer1-brand"></div>
        <p class="footer1-text10">
          <slot name="text">
            <!--Default content for text-->
            <div class="footer1-fragment23">
              <span class="footer1-text28">Follow Us:</span>
            </div>
          </slot>
        </p>
        <div class="footer1-socials">
          <div class="social">
            <img :alt="imageAlt1" :src="imageSrc1" class="footer1-image2" />
          </div>
          <div class="social">
            <img :alt="imageAlt2" :src="imageSrc2" class="footer1-image3" />
          </div>
          <div class="social">
            <img :alt="imageAlt3" :src="imageSrc3" class="footer1-image4" />
          </div>
        </div>
        <div class="footer1-legal1">
          <span class="footer1-copyright1">
            <slot name="copyright3">
              <!--Default content for copyright3-->
              <div class="footer1-fragment22">
                <span class="footer1-text27">
                  © 2025 NovaTec. All Rights Reserved.
                </span>
              </div>
            </slot>
          </span>
          <span class="legal-link">
            <slot name="copyright4">
              <!--Default content for copyright4-->
              <div class="footer1-fragment31">
                <span class="footer1-text37">Privacy Policy</span>
              </div>
            </slot>
          </span>
          <span class="legal-link">
            <slot name="copyright5">
              <!--Default content for copyright5-->
              <div class="footer1-fragment25">
                <span class="footer1-text31">Terms of Use</span>
              </div>
            </slot>
          </span>
        </div>
      </div>
    </div>
    <div class="footer1-container2">
      <div class="footer1-list1">
        <span class="footer1-header1">
          <slot name="header">
            <!--Default content for header-->
            <div class="footer1-fragment20">
              <span class="footer1-text25">Contact</span>
            </div>
          </slot>
        </span>
        <div class="footer1-links1">
          <span class="footer1-link10">
            <slot name="link">
              <!--Default content for link-->
              <div class="footer1-fragment14">
                <span class="footer1-text15">
                  48 شارع عبد الرازق الستوري مدينة نصر القاهرة
                </span>
              </div>
            </slot>
          </span>
          <a
            href="mailto:contact@template.new?subject=Main"
            class="footer1-link11"
          >
            <slot name="link1">
              <!--Default content for link1-->
              <div class="footer1-fragment29">
                <span class="footer1-text35">Adamamrabdelnabi2008@gmail.com</span>
              </div>
            </slot>
          </a>
          <a href="tel:(004) 234 - 5678" class="footer1-link12">
            <slot name="link2">
              <!--Default content for link2-->
              <div class="footer1-fragment24">
                <a href="tel:(004) 234 - 5678" class="footer1-link24">
                  <span>+20 </span>
                  <span>1012221123</span>
                </a>
              </div>
            </slot>
          </a>
        </div>
        <div class="footer1-links2">
          <span class="footer1-link13">
            <slot name="link3">
              <!--Default content for link3-->
              <div class="footer1-fragment18">
                <span class="footer1-link23">
                  <span class="footer1-text19">
                    Manufacture Location: ELHODA TRADE AND SUPPLIES
                  </span>
                  <br />
                  <span class="footer1-text21">
                    28-29-30/2 Food and Pharmaceutical region
                  </span>
                  <br />
                  <span class="footer1-text23">
                    Zone C ,Badr Industrial City , CAIRO ,EGYPT.
                  </span>
                </span>
              </div>
            </slot>
          </span>
        </div>
      </div>
      <div class="footer1-container3">
        <div class="footer1-right">
          <div class="footer1-list2">
            <span class="footer1-header2">
              <slot name="header1">
                <!--Default content for header1-->
                <div class="footer1-fragment11">
                  <span class="footer1-text12">Menu</span>
                </div>
              </slot>
            </span>
            <div class="footer1-links3">
              <a href="#how-it-works" class="footer1-link14">
                <slot name="link4">
                  <!--Default content for link4-->
                  <div class="footer1-fragment16">
                    <span class="footer1-text17">Home</span>
                  </div>
                </slot>
              </a>
              <a href="#how-it-works" class="footer1-link15">
                <slot name="link5">
                  <!--Default content for link5-->
                  <div class="footer1-fragment13">
                    <span class="footer1-text14">About</span>
                  </div>
                </slot>
              </a>
              <a href="#Our Products" class="footer1-link16">
                <slot name="link6">
                  <!--Default content for link6-->
                  <div class="footer1-fragment21">
                    <span class="footer1-text26">Services</span>
                  </div>
                </slot>
              </a>
              <a href="#News" class="footer1-link17">
                <slot name="link7">
                  <!--Default content for link7-->
                  <div class="footer1-fragment30">
                    <span class="footer1-text36">Blog</span>
                  </div>
                </slot>
              </a>
              <span class="footer1-link18">
                <slot name="link8">
                  <!--Default content for link8-->
                  <div class="footer1-fragment10">
                    <span class="footer1-text11">Support</span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="footer1-list3">
            <span class="footer1-header3">
              <slot name="header2">
                <!--Default content for header2-->
                <div class="footer1-fragment17">
                  <span class="footer1-text18">Resources</span>
                </div>
              </slot>
            </span>
            <div class="footer1-links4">
              <span class="footer1-link19">
                <slot name="link9">
                  <!--Default content for link9-->
                  <div class="footer1-fragment28">
                    <span class="footer1-text34">Test Results</span>
                  </div>
                </slot>
              </span>
              <span class="footer1-link20">
                <slot name="link10">
                  <!--Default content for link10-->
                  <div class="footer1-fragment27">
                    <span class="footer1-text33">Patients</span>
                  </div>
                </slot>
              </span>
              <a href="#Team8" class="footer1-link21">
                <slot name="link11">
                  <!--Default content for link11-->
                  <div class="footer1-fragment26">
                    <span class="footer1-text32">Doctors</span>
                  </div>
                </slot>
              </a>
              <span class="footer1-link22">
                <slot name="link12">
                  <!--Default content for link12-->
                  <div class="footer1-fragment32">
                    <span class="footer1-text38">Health</span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer1-legal2">
      <div class="footer1-row">
        <span class="legal-link">
          <slot name="copyright1">
            <!--Default content for copyright1-->
            <div class="footer1-fragment15">
              <span class="footer1-text16">Privacy Policy</span>
            </div>
          </slot>
        </span>
        <span class="legal-link">
          <slot name="copyright2">
            <!--Default content for copyright2-->
            <div class="footer1-fragment12">
              <span class="footer1-text13">Terms of Use</span>
            </div>
          </slot>
        </span>
      </div>
      <span class="footer1-copyright6">
        <slot name="copyright">
          <!--Default content for copyright-->
          <div class="footer1-fragment19">
            <span class="footer1-text24">
              © 2025 NovaTec. All Rights Reserved.
            </span>
          </div>
        </slot>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer1',
  props: {
    imageAlt1: {
      type: String,
      default: 'image',
    },
    imageSrc1: {
      type: String,
      default: '/Icons/insider.svg',
    },
    imageSrc3: {
      type: String,
      default: '/Icons/twitter.svg',
    },
    imageSrc: {
      type: String,
      default: '/nova_tec-200h.jpg',
    },
    imageAlt2: {
      type: String,
      default: 'image',
    },
    imageSrc2: {
      type: String,
      default: '/Icons/instagram.svg',
    },
    imageAlt: {
      type: String,
      default: 'image',
    },
    imageAlt3: {
      type: String,
      default: 'image',
    },
  },
}
</script>

<style scoped>
.footer1-footer {
  width: 100%;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  padding-top: 120px;
  padding-left: var(--dl-layout-space-fiveunits);
  padding-right: var(--dl-layout-space-fiveunits);
  flex-direction: row;
  padding-bottom: var(--dl-layout-space-fiveunits);
  justify-content: space-between;
  background-color: #334a53;
}
 
.footer1-container1 {
  width: 372px;
  height: auto;
  display: flex;
  align-items: space-between;
  flex-direction: column;
  background-color: #334a53;
}
 
.footer1-image1 {
  width: 268px;
  height: 72px;
  object-fit: cover;
}
 
.footer1-left {
  gap: var(--dl-layout-space-threeunits);
  width: 355px;
  display: flex;
  align-items: flex-start;
  padding-right: var(--dl-layout-space-threeunits);
  flex-direction: column;
}
 
.footer1-brand {
  gap: var(--dl-layout-space-unit);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  max-width: 400px;
  align-items: flex-start;
  flex-direction: column;
}
 
.footer1-text10 {
  color: rgb(255, 255, 255);
}
 
.footer1-socials {
  gap: var(--dl-layout-space-unit);
  display: flex;
  max-width: 400px;
  align-items: flex-start;
  flex-direction: row;
}
 
.footer1-image2 {
  width: 24px;
  object-fit: cover;
}
 
.footer1-image3 {
  width: 24px;
  object-fit: cover;
}
 
.footer1-image4 {
  width: 24px;
  object-fit: cover;
}
 
.footer1-legal1 {
  gap: var(--dl-layout-space-threeunits);
  width: 344px;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.footer1-copyright1 {
  color: rgb(255, 255, 255);
}
 
.footer1-container2 {
  flex: 0 0 auto;
  width: 784px;
  height: auto;
  display: flex;
  align-items: space-between;
  flex-direction: column;
}
 
.footer1-list1 {
  gap: var(--dl-layout-space-unit);
  flex: 1;
  width: 760px;
  display: flex;
  overflow: hidden;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.footer1-header1 {
  color: rgb(255, 255, 255);
  font-style: normal;
  font-weight: 600;
}
 
.footer1-links1 {
  gap: 12px;
  width: 458px;
  height: 116px;
  display: flex;
  margin-top: 0px;
  align-items: flex-start;
  margin-left: 0px;
  margin-bottom: var(--dl-layout-space-twounits);
  flex-direction: column;
}
 
.footer1-link10 {
  color: rgb(255, 255, 255);
  width: 100%;
  cursor: pointer;
  font-size: 20px;
  transition: 0.3s;
}
 
.footer1-link10:hover {
  opacity: 0.5;
}
 
.footer1-link11 {
  color: rgb(255, 255, 255);
  width: 215px;
  cursor: pointer;
  display: block;
  font-size: 16px;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link11:hover {
  opacity: 0.5;
}
 
.footer1-link12 {
  color: rgb(255, 255, 255);
  width: 215px;
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link12:hover {
  opacity: 0.5;
}
 
.footer1-links2 {
  gap: 12px;
  width: 556px;
  height: 116px;
  display: flex;
  margin-top: 0px;
  align-items: flex-start;
  margin-left: 0px;
  margin-right: 0px;
  margin-bottom: var(--dl-layout-space-twounits);
  flex-direction: column;
}
 
.footer1-link13 {
  color: rgb(255, 255, 255);
  width: 100%;
  cursor: pointer;
  font-size: 19px;
  transition: 0.3s;
}
 
.footer1-link13:hover {
  opacity: 0.5;
}
 
.footer1-container3 {
  flex: 0 0 auto;
  width: 784px;
  height: auto;
  display: flex;
  align-items: space-between;
  flex-direction: column;
}
 
.footer1-right {
  gap: var(--dl-layout-space-sixunits);
  width: 784px;
  height: 246px;
  display: flex;
  overflow: hidden;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
}
 
.footer1-list2 {
  gap: var(--dl-layout-space-unit);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.footer1-header2 {
  color: rgb(255, 255, 255);
  font-style: normal;
  font-weight: 600;
}
 
.footer1-links3 {
  gap: 12px;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.footer1-link14 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link14:hover {
  opacity: 0.5;
}
 
.footer1-link15 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link15:hover {
  opacity: 0.5;
}
 
.footer1-link16 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link16:hover {
  opacity: 0.5;
}
 
.footer1-link17 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link17:hover {
  opacity: 0.5;
}
 
.footer1-link18 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
}
 
.footer1-link18:hover {
  opacity: 0.5;
}
 
.footer1-list3 {
  gap: var(--dl-layout-space-unit);
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.footer1-header3 {
  color: rgb(255, 255, 255);
  font-style: normal;
  font-weight: 600;
}
 
.footer1-links4 {
  gap: 12px;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.footer1-link19 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
}
 
.footer1-link19:hover {
  opacity: 0.5;
}
 
.footer1-link20 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
}
 
.footer1-link20:hover {
  opacity: 0.5;
}
 
.footer1-link21 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link21:hover {
  opacity: 0.5;
}
 
.footer1-link22 {
  color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.3s;
}
 
.footer1-link22:hover {
  opacity: 0.5;
}
 
.footer1-legal2 {
  gap: var(--dl-layout-space-threeunits);
  width: 100%;
  display: none;
  align-items: flex-start;
  flex-direction: row;
}
 
.footer1-row {
  display: flex;
}
 
.footer1-copyright6 {
  color: rgb(255, 255, 255);
  font-size: 12px;
}
 
.footer1-fragment10 {
  display: contents;
}
 
.footer1-text11 {
  display: inline-block;
}
 
.footer1-fragment11 {
  display: contents;
}
 
.footer1-text12 {
  display: inline-block;
}
 
.footer1-fragment12 {
  display: contents;
}
 
.footer1-text13 {
  display: inline-block;
}
 
.footer1-fragment13 {
  display: contents;
}
 
.footer1-text14 {
  display: inline-block;
}
 
.footer1-fragment14 {
  display: contents;
}
 
.footer1-text15 {
  display: inline-block;
}
 
.footer1-fragment15 {
  display: contents;
}
 
.footer1-text16 {
  display: inline-block;
}
 
.footer1-fragment16 {
  display: contents;
}
 
.footer1-text17 {
  display: inline-block;
}
 
.footer1-fragment17 {
  display: contents;
}
 
.footer1-text18 {
  display: inline-block;
}
 
.footer1-fragment18 {
  display: contents;
}
 
.footer1-link23 {
  color: rgb(255, 255, 255);
  width: 100%;
  cursor: pointer;
  display: inline-block;
  font-size: 19px;
  transition: 0.3s;
}
 
.footer1-link23:hover {
  opacity: 0.5;
}
 
.footer1-text19:hover {
  opacity: 0.5;
}
 
.footer1-text21:hover {
  opacity: 0.5;
}
 
.footer1-text23:hover {
  opacity: 0.5;
}
 
.footer1-fragment19 {
  display: contents;
}
 
.footer1-text24 {
  display: inline-block;
}
 
.footer1-fragment20 {
  display: contents;
}
 
.footer1-text25 {
  display: inline-block;
}
 
.footer1-fragment21 {
  display: contents;
}
 
.footer1-text26 {
  display: inline-block;
}
 
.footer1-fragment22 {
  display: contents;
}
 
.footer1-text27 {
  display: inline-block;
}
 
.footer1-fragment23 {
  display: contents;
}
 
.footer1-text28 {
  display: inline-block;
}
 
.footer1-fragment24 {
  display: contents;
}
 
.footer1-link24 {
  color: rgb(255, 255, 255);
  width: 215px;
  cursor: pointer;
  display: inline-block;
  transition: 0.3s;
  text-decoration: none;
}
 
.footer1-link24:hover {
  opacity: 0.5;
}
 
.footer1-fragment25 {
  display: contents;
}
 
.footer1-text31 {
  display: inline-block;
}
 
.footer1-fragment26 {
  display: contents;
}
 
.footer1-text32 {
  display: inline-block;
}
 
.footer1-fragment27 {
  display: contents;
}
 
.footer1-text33 {
  display: inline-block;
}
 
.footer1-fragment28 {
  display: contents;
}
 
.footer1-text34 {
  display: inline-block;
}
 
.footer1-fragment29 {
  display: contents;
}
 
.footer1-text35 {
  display: inline-block;
}
 
.footer1-fragment30 {
  display: contents;
}
 
.footer1-text36 {
  display: inline-block;
}
 
.footer1-fragment31 {
  display: contents;
}
 
.footer1-text37 {
  display: inline-block;
}
 
.footer1-fragment32 {
  display: contents;
}
 
.footer1-text38 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .footer1-footer {
    gap: 100px;
    align-items: flex-start;
    flex-direction: column;
    justify-content: flex-start;
  }
  .footer1-left {
    padding-right: 0px;
  }
  .footer1-socials {
    display: none;
  }
  .footer1-legal1 {
    display: none;
  }
  .footer1-right {
    gap: var(--dl-layout-space-twounits);
    flex-direction: column;
  }
  .footer1-legal2 {
    gap: var(--dl-layout-space-twounits);
    display: flex;
    flex-direction: column;
  }
  .footer1-row {
    gap: var(--dl-layout-space-oneandhalfunits);
  }
}
 
@media(max-width: 767px) {
  .footer1-footer {
    padding-top: var(--dl-layout-space-fourunits);
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
    padding-bottom: var(--dl-layout-space-threeunits);
  }
  .footer1-text10 {
    font-size: 12px;
    line-height: 18px;
  }
}
 
@media(max-width: 479px) {
  .footer1-copyright6 {
    color: rgb(255, 255, 255);
    font-size: 12px;
  }
}
</style>
