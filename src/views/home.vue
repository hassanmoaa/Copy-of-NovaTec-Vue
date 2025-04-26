<template>
  <div class="home-container1">
    <section class="home-hero">
      <header class="home-header1">
        <header data-thq="thq-navbar" class="home-navbar">
          <div class="home-left">
            <img alt="image" src="/nova_tec-200h.jpg" class="home-image1" />
            <div class="home-container2">
              <nav class="home-links">
                <a href="#how-it-works" class="home-link1">About Us</a>
                <a href="#features" class="home-link2">
                  <span>S</span>
                  <span>ervices</span>
                </a>
                <span class="home-link3">Prices</span>
                <a href="#Footer" class="home-link4">Contact Us</a>
              </nav>
            </div>
          </div>
          <div data-thq="thq-burger-menu" class="home-burger-menu">
            <svg viewBox="0 0 1024 1024" class="home-icon1">
              <path
                d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path>
            </svg>
          </div>
          <div data-thq="thq-mobile-menu" class="home-mobile-menu">
            <div data-thq="thq-mobile-menu-nav" data-role="Nav" class="home-nav1">
              <div class="home-container3">
                <div data-thq="thq-close-menu" class="home-menu-close">
                  <svg viewBox="0 0 1024 1024" class="home-icon3">
                    <path
                      d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                    ></path>
                  </svg>
                </div>
              </div>
              <nav
                data-thq="thq-mobile-menu-nav-links"
                data-role="Nav"
                class="home-nav2"
              >
                <span class="home-text102">Features</span>
                <span class="home-text103">How it works</span>
                <span class="home-text104">Prices</span>
                <span class="home-text105">Contact</span>
              </nav>
            </div>
          </div>
        </header>
      </header>
      <div class="home-main">
        <div class="home-content1">
          <div class="home-heading">
            <h1 class="home-header2">
              Experienced general practitioners who have an eye for your care
            </h1>
            <p class="home-caption1">
              We are a leading provider of advanced medical solutions dedicated to
              improving patient care and enhancing recovery.
              <span v-html="raw7nxh"></span>
            </p>
          </div>
          <button class="button button-main home-book">
            <span>Our Products --&gt;</span>
          </button>
        </div>
        <div class="home-image2">
          <img alt="image" src="/doctor-image-1500w.png" class="home-image3" />
        </div>
      </div>
      <div id="features" class="home-features">
        <div class="home-content2">
          <app-features title="Services" class="home-component1"></app-features>
          <app-features title=" Trainings"></app-features>
          <app-features
            title=" Innovations"
            description="Lorem ipsum dolor sit amet, consectetur adipiscing elit."
          ></app-features>
        </div>
      </div>
      <app-background rootClassName="backgroundroot-class-name1"></app-background>
    </section>
    <app-component>
      <template v-slot:heading>
        <div class="home-fragment10">
          <span class="home-text107">Our Manufacture</span>
        </div>
      </template>
    </app-component>
    <our-products
      ourProductsId="Our Products"
      rootClassName="our-productsroot-class-name"
    >
      <template v-slot:text>
        <div class="home-fragment11">
          <span class="home-text108">
            <span class="home-text109">
              Our portfolio spans a wide range of medical specialties, ensuring
              comprehensive support for diverse clinical needs.                   
                 
            </span>
            <br class="home-text110" />
            <span>
              Advanced solutions to support wound healing and reduce infection
              risk.
            </span>
            <br class="home-text112" />
          </span>
        </div>
      </template>
      <template v-slot:text1>
        <div class="home-fragment12">
          <span class="home-text113">All practices</span>
        </div>
      </template>
      <template v-slot:header>
        <div class="home-fragment13">
          <span class="home-text114">Endoscopy</span>
        </div>
      </template>
      <template v-slot:caption>
        <div class="home-fragment14">
          <span class="home-caption2">
            <span>-Arthoscopy</span>
            <br />
            <span>-Lapurscopy</span>
            <br />
            <span>-Urology</span>
            <br />
            <span>-ENT</span>
            <br />
            <span>-Spine</span>
          </span>
        </div>
      </template>
      <template v-slot:header1>
        <div class="home-fragment15">
          <span class="home-text124">Physiotherapy</span>
        </div>
      </template>
      <template v-slot:header2>
        <div class="home-fragment16">
          <span class="home-text125">Orthopedics</span>
        </div>
      </template>
      <template v-slot:header3>
        <div class="home-fragment17">
          <span class="home-text126">Drills</span>
        </div>
      </template>
      <template v-slot:header4>
        <div class="home-fragment18">
          <span class="home-text127">Plasma Coblators</span>
        </div>
      </template>
      <template v-slot:heading>
        <div class="home-fragment19">
          <span class="home-text128">Our Services</span>
        </div>
      </template>
      <template v-slot:caption1>
        <div class="home-fragment20">
          <span class="home-caption3">
            <span>-CPM</span>
            <br />
            <span>-Electric</span>
            <br />
            <span>-Tractions</span>
            <br />
            <span>-ULS</span>
            <br />
            <span>-Laser</span>
            <br />
            <span>-Others</span>
          </span>
        </div>
      </template>
      <template v-slot:caption2>
        <div class="home-fragment21">
          <span class="home-caption4">
            <span>1. Arthroplasty</span>
            <br />
            <span>- Knee</span>
            <br />
            <span>- Hips</span>
            <br />
            <span>- Shoulder</span>
            <br />
            <span>- Elbow</span>
            <br />
            <br />
            <span>2. Spine</span>
            <br />
            <span>3. Trauma</span>
            <br />
            <span>4. Sports-Medicine</span>
          </span>
        </div>
      </template>
      <template v-slot:caption3>
        <div class="home-fragment22">
          <span class="home-caption5">
            <span>-Orthopectic</span>
            <br />
            <span>-Neurosurgery</span>
            <br />
            <span>-Sternum-Cardiosurgery</span>
            <br />
            <span>-Others</span>
            <br />
            <span>-Minidrills</span>
            <br />
            <span>-Saws</span>
            <br />
          </span>
        </div>
      </template>
      <template v-slot:caption4>
        <div class="home-fragment23">
          <span class="home-caption6">
            <span>-Arthoscopy</span>
            <br />
            <br class="home-text170" />
            <span>-Spine</span>
            <br />
            <br class="home-text173" />
            <span>-ENT</span>
            <br />
            <br class="home-text176" />
            <span>-Urology</span>
            <span class="home-text178"><span v-html="rawgj43"></span></span>
            <br class="home-text179" />
          </span>
        </div>
      </template>
    </our-products>
    <app-component1>
      <template v-slot:text>
        <div class="home-fragment24">
          <span class="home-text180">
            <span>• Scientific Activities</span>
            <br />
            <span>• Training</span>
            <br />
            <span>• Services</span>
            <br />
            <span>• Innovations</span>
            <br />
            <br />
          </span>
        </div>
      </template>
      <template v-slot:header>
        <div class="home-fragment25">
          <span class="home-header3">
            <span><span v-html="raw3o7i"></span></span>
            <span class="home-text191">
              1. Research / Scientific Activities / Training
            </span>
            <br />
          </span>
        </div>
      </template>
      <template v-slot:header1>
        <div class="home-fragment26">
          <span class="home-header4">
            <span class="home-text193">
              2. Supervision &amp; Tracing of new products &amp; implements
            </span>
            <br />
          </span>
        </div>
      </template>
      <template v-slot:header2>
        <div class="home-fragment27">
          <span class="home-header5">
            <span class="home-text195">
              3. Engineering, Maintenance (of Equipment), Programmes
            </span>
            <br />
          </span>
        </div>
      </template>
      <template v-slot:header3>
        <div class="home-fragment28">
          <span class="home-header6">
            <span class="home-text197">4. Teamwork / Follow-up</span>
            <br />
          </span>
        </div>
      </template>
      <template v-slot:header4>
        <div class="home-fragment29">
          <span class="home-text199">5. Customers Training &amp; Upgrading</span>
        </div>
      </template>
      <template v-slot:header5>
        <div class="home-fragment30">
          <span class="home-text200">
            6. Scientific Groups, Societies, and Activities
          </span>
        </div>
      </template>
      <template v-slot:header6>
        <div class="home-fragment31">
          <span class="home-text201">7. Share Experiences Internationally</span>
        </div>
      </template>
      <template v-slot:header7>
        <div class="home-fragment32">
          <span class="home-text202">
            8. Clinical Groups for More Achievement, More Operations, and More
            Research Papers
          </span>
        </div>
      </template>
      <template v-slot:header8>
        <div class="home-fragment33">
          <span class="home-text203">9. Our Scientific Sheets</span>
        </div>
      </template>
      <template v-slot:heading>
        <div class="home-fragment34">
          <span class="home-text204">Scientific Life</span>
        </div>
      </template>
    </app-component1>
    <div data-thq="slider-slide" class="home-slider-slide1 swiper-slide"></div>
    <div data-thq="slider-slide" class="home-slider-slide2 swiper-slide"></div>
    <div data-thq="slider-slide" class="swiper-slide"></div>
    <app-footer1>
      <template v-slot:link>
        <div class="home-fragment35">
          <span class="home-text205">
            48 شارع عبد الرازق الستوري مدينة نصر القاهرة
          </span>
        </div>
      </template>
      <template v-slot:text>
        <div class="home-fragment36">
          <span class="home-text206">Follow Us:</span>
        </div>
      </template>
      <template v-slot:link1>
        <div class="home-fragment37">
          <span class="home-text207">Adamamrabdelnabi2008@gmail.com</span>
        </div>
      </template>
      <template v-slot:link2>
        <div class="home-fragment38">
          <a href="tel:(004) 234 - 5678" class="home-link5">
            <span>+20 </span>
            <span>1012221123</span>
          </a>
        </div>
      </template>
      <template v-slot:link3>
        <div class="home-fragment39">
          <span class="home-link6">
            <span class="home-text210">
              Manufacture Location: ELHODA TRADE AND SUPPLIES
            </span>
            <br />
            <span class="home-text212">
              28-29-30/2 Food and Pharmaceutical region
            </span>
            <br />
            <span class="home-text214">
              Zone C ,Badr Industrial City , CAIRO ,EGYPT.
            </span>
          </span>
        </div>
      </template>
      <template v-slot:link4>
        <div class="home-fragment40"><span class="home-text215">Home</span></div>
      </template>
      <template v-slot:link5>
        <div class="home-fragment41"><span class="home-text216">About</span></div>
      </template>
      <template v-slot:link6>
        <div class="home-fragment42">
          <span class="home-text217">Services</span>
        </div>
      </template>
      <template v-slot:link7>
        <div class="home-fragment43"><span class="home-text218">Blog</span></div>
      </template>
      <template v-slot:link8>
        <div class="home-fragment44">
          <span class="home-text219">Support</span>
        </div>
      </template>
      <template v-slot:link9>
        <div class="home-fragment45">
          <span class="home-text220">Test Results</span>
        </div>
      </template>
      <template v-slot:header>
        <div class="home-fragment46">
          <span class="home-text221">Contact</span>
        </div>
      </template>
      <template v-slot:link10>
        <div class="home-fragment47">
          <span class="home-text222">Patients</span>
        </div>
      </template>
      <template v-slot:link11>
        <div class="home-fragment48">
          <span class="home-text223">Doctors</span>
        </div>
      </template>
      <template v-slot:link12>
        <div class="home-fragment49">
          <span class="home-text224">Health</span>
        </div>
      </template>
      <template v-slot:header1>
        <div class="home-fragment50"><span class="home-text225">Menu</span></div>
      </template>
      <template v-slot:header2>
        <div class="home-fragment51">
          <span class="home-text226">Resources</span>
        </div>
      </template>
      <template v-slot:copyright>
        <div class="home-fragment52">
          <span class="home-text227">© 2025 NovaTec. All Rights Reserved.</span>
        </div>
      </template>
      <template v-slot:copyright1>
        <div class="home-fragment53">
          <span class="home-text228">Privacy Policy</span>
        </div>
      </template>
      <template v-slot:copyright2>
        <div class="home-fragment54">
          <span class="home-text229">Terms of Use</span>
        </div>
      </template>
      <template v-slot:copyright3>
        <div class="home-fragment55">
          <span class="home-text230">© 2025 NovaTec. All Rights Reserved.</span>
        </div>
      </template>
      <template v-slot:copyright4>
        <div class="home-fragment56">
          <span class="home-text231">Privacy Policy</span>
        </div>
      </template>
      <template v-slot:copyright5>
        <div class="home-fragment57">
          <span class="home-text232">Terms of Use</span>
        </div>
      </template>
    </app-footer1>
  </div>
</template>

<script>
import AppFeatures from '../components/features'
import AppBackground from '../components/background'
import AppComponent from '../components/component'
import OurProducts from '../components/our-products'
import AppComponent1 from '../components/component1'
import AppFooter1 from '../components/footer1'

export default {
  name: 'Home',
  props: {},
  components: {
    AppFeatures,
    AppBackground,
    AppComponent,
    OurProducts,
    AppComponent1,
    AppFooter1,
  },
  data() {
    return {
      raw7nxh: ' ',
      rawgj43: ' ',
      raw3o7i: ' ',
    }
  },
  metaInfo: {
    title: 'NovaTec',
    meta: [
      {
        property: 'og:title',
        content: 'NovaTec',
      },
    ],
  },
}
</script>

<style scoped>
.home-container1 {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  scroll-behavior: smooth;
}
 
.home-hero {
  width: 100%;
  height: 100vh;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
 
.home-header1 {
  width: 100%;
  display: flex;
  justify-content: center;
}
 
.home-navbar {
  flex: 1;
  width: 100%;
  display: flex;
  z-index: 100;
  overflow: hidden;
  max-width: var(--dl-layout-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-layout-space-oneandhalfunits);
  padding-left: var(--dl-layout-space-fiveunits);
  padding-right: var(--dl-layout-space-fiveunits);
  padding-bottom: var(--dl-layout-space-oneandhalfunits);
  justify-content: space-between;
  background-color: #334a53;
}
 
.home-left {
  gap: var(--dl-layout-space-twounits);
  display: flex;
  align-items: center;
  margin-right: 29px;
  justify-content: center;
}
 
.home-image1 {
  width: 296px;
  height: 86px;
  object-fit: cover;
}
 
.home-container2 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.home-links {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-items: center;
  justify-content: center;
}
 
.home-link1 {
  color: #ffffff;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
 
.home-link2 {
  color: #ffffff;
  cursor: pointer;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
  text-decoration: none;
}
 
.home-link2:hover {
  opacity: 0.5;
}
 
.home-link3 {
  color: #ffffff;
  cursor: pointer;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
}
 
.home-link3:hover {
  opacity: 0.5;
}
 
.home-link4 {
  color: #ffffff;
  cursor: pointer;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
  text-decoration: none;
}
 
.home-link4:hover {
  opacity: 0.5;
}
 
.home-burger-menu {
  display: none;
  align-items: center;
  justify-content: center;
}
 
.home-icon1 {
  width: var(--dl-layout-size-xsmall);
  height: var(--dl-layout-size-xsmall);
}
 
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 1000;
  position: fixed;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
 
.home-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.home-container3 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-layout-space-threeunits);
  justify-content: space-between;
}
 
.home-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
 
.home-icon3 {
  width: var(--dl-layout-size-xsmall);
  height: var(--dl-layout-size-xsmall);
}
 
.home-nav2 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.home-text102 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.home-text103 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.home-text104 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.home-text105 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.home-main {
  flex: 1;
  width: 100%;
  display: flex;
  z-index: 100;
  overflow: hidden;
  max-width: var(--dl-layout-size-maxwidth);
  align-items: stretch;
  padding-left: var(--dl-layout-space-fiveunits);
  flex-direction: row;
  justify-content: space-between;
  background-color: #334a53;
}
 
.home-content1 {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-oneandhalfunits);
  justify-content: center;
}
 
.home-heading {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.home-header2 {
  color: #ffffff;
  width: 100%;
  font-size: 62px;
  max-width: 750px;
  font-style: normal;
  font-weight: 600;
  line-height: 74px;
}
 
.home-caption1 {
  color: rgb(255, 255, 255);
  width: 100%;
  font-size: 18px;
  max-width: 600px;
  line-height: 27px;
}
 
.home-image2 {
  flex: 1;
  display: flex;
  overflow: hidden;
  max-width: 100%;
  align-items: flex-end;
  padding-right: var(--dl-layout-space-fiveunits);
  flex-direction: row;
  justify-content: center;
}
 
.home-image3 {
  height: 95%;
  object-fit: cover;
}
 
.home-features {
  width: 100%;
  display: flex;
  z-index: 100;
  overflow: hidden;
  align-items: center;
  padding-top: var(--dl-layout-space-fiveunits);
  flex-direction: row;
  padding-bottom: var(--dl-layout-space-fiveunits);
  justify-content: center;
  background-color: #1c587d;
}
 
.home-content2 {
  gap: var(--dl-layout-space-threeunits);
  flex: 1;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-left: var(--dl-layout-space-fiveunits);
  padding-right: var(--dl-layout-space-fiveunits);
  flex-direction: row;
}
 
.home-component1 {
  text-decoration: none;
}
 
.home-fragment10 {
  display: contents;
}
 
.home-text107 {
  display: inline-block;
}
 
.home-fragment11 {
  display: contents;
}
 
.home-text108 {
  height: 276px;
  display: inline-block;
  font-size: 18px;
  max-width: 385px;
  line-height: 27px;
}
 
.home-text110 {
  font-size: 18px;
  line-height: 27px;
}
 
.home-fragment12 {
  display: contents;
}
 
.home-text113 {
  display: inline-block;
}
 
.home-fragment13 {
  display: contents;
}
 
.home-text114 {
  display: inline-block;
}
 
.home-fragment14 {
  display: contents;
}
 
.home-caption2 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.home-fragment15 {
  display: contents;
}
 
.home-text124 {
  display: inline-block;
}
 
.home-fragment16 {
  display: contents;
}
 
.home-text125 {
  display: inline-block;
}
 
.home-fragment17 {
  display: contents;
}
 
.home-text126 {
  display: inline-block;
}
 
.home-fragment18 {
  display: contents;
}
 
.home-text127 {
  display: inline-block;
}
 
.home-fragment19 {
  display: contents;
}
 
.home-text128 {
  display: inline-block;
}
 
.home-fragment20 {
  display: contents;
}
 
.home-caption3 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.home-fragment21 {
  display: contents;
}
 
.home-caption4 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.home-fragment22 {
  display: contents;
}
 
.home-caption5 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.home-fragment23 {
  display: contents;
}
 
.home-caption6 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.home-fragment24 {
  display: contents;
}
 
.home-text180 {
  height: 276px;
  display: inline-block;
  font-size: 18px;
  max-width: 385px;
  line-height: 27px;
}
 
.home-fragment25 {
  display: contents;
}
 
.home-header3 {
  width: 240px;
  display: inline-block;
  line-height: 36px;
}
 
.home-text191 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.home-fragment26 {
  display: contents;
}
 
.home-header4 {
  display: inline-block;
  line-height: 36px;
}
 
.home-text193 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.home-fragment27 {
  display: contents;
}
 
.home-header5 {
  display: inline-block;
  line-height: 36px;
}
 
.home-text195 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.home-fragment28 {
  display: contents;
}
 
.home-header6 {
  display: inline-block;
  line-height: 36px;
}
 
.home-text197 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.home-fragment29 {
  display: contents;
}
 
.home-text199 {
  display: inline-block;
}
 
.home-fragment30 {
  display: contents;
}
 
.home-text200 {
  display: inline-block;
}
 
.home-fragment31 {
  display: contents;
}
 
.home-text201 {
  display: inline-block;
}
 
.home-fragment32 {
  display: contents;
}
 
.home-text202 {
  display: inline-block;
}
 
.home-fragment33 {
  display: contents;
}
 
.home-text203 {
  display: inline-block;
}
 
.home-fragment34 {
  display: contents;
}
 
.home-text204 {
  display: inline-block;
}
 
.home-slider-slide1 {
  display: none;
  background-size: 100%;
  background-image: url('https://images.unsplash.com/photo-1697384333613-de519c7367c4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY5OTk3NzAzN3w&ixlib=rb-4.0.3&q=80&w=1500');
}
 
.home-slider-slide2 {
  display: none;
  background-size: 100%;
  background-image: url('https://images.unsplash.com/photo-1698180687511-bd6c0104ee98?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY5OTk3NzQ5NXw&ixlib=rb-4.0.3&q=80&w=1080');
}
 
.home-fragment35 {
  display: contents;
}
 
.home-text205 {
  display: inline-block;
}
 
.home-fragment36 {
  display: contents;
}
 
.home-text206 {
  display: inline-block;
}
 
.home-fragment37 {
  display: contents;
}
 
.home-text207 {
  display: inline-block;
}
 
.home-fragment38 {
  display: contents;
}
 
.home-link5 {
  color: rgb(255, 255, 255);
  width: 215px;
  cursor: pointer;
  display: inline-block;
  transition: 0.3s;
  text-decoration: none;
}
 
.home-link5:hover {
  opacity: 0.5;
}
 
.home-fragment39 {
  display: contents;
}
 
.home-link6 {
  color: rgb(255, 255, 255);
  width: 100%;
  cursor: pointer;
  display: inline-block;
  font-size: 19px;
  transition: 0.3s;
}
 
.home-link6:hover {
  opacity: 0.5;
}
 
.home-text210:hover {
  opacity: 0.5;
}
 
.home-text212:hover {
  opacity: 0.5;
}
 
.home-text214:hover {
  opacity: 0.5;
}
 
.home-fragment40 {
  display: contents;
}
 
.home-text215 {
  display: inline-block;
}
 
.home-fragment41 {
  display: contents;
}
 
.home-text216 {
  display: inline-block;
}
 
.home-fragment42 {
  display: contents;
}
 
.home-text217 {
  display: inline-block;
}
 
.home-fragment43 {
  display: contents;
}
 
.home-text218 {
  display: inline-block;
}
 
.home-fragment44 {
  display: contents;
}
 
.home-text219 {
  display: inline-block;
}
 
.home-fragment45 {
  display: contents;
}
 
.home-text220 {
  display: inline-block;
}
 
.home-fragment46 {
  display: contents;
}
 
.home-text221 {
  display: inline-block;
}
 
.home-fragment47 {
  display: contents;
}
 
.home-text222 {
  display: inline-block;
}
 
.home-fragment48 {
  display: contents;
}
 
.home-text223 {
  display: inline-block;
}
 
.home-fragment49 {
  display: contents;
}
 
.home-text224 {
  display: inline-block;
}
 
.home-fragment50 {
  display: contents;
}
 
.home-text225 {
  display: inline-block;
}
 
.home-fragment51 {
  display: contents;
}
 
.home-text226 {
  display: inline-block;
}
 
.home-fragment52 {
  display: contents;
}
 
.home-text227 {
  display: inline-block;
}
 
.home-fragment53 {
  display: contents;
}
 
.home-text228 {
  display: inline-block;
}
 
.home-fragment54 {
  display: contents;
}
 
.home-text229 {
  display: inline-block;
}
 
.home-fragment55 {
  display: contents;
}
 
.home-text230 {
  display: inline-block;
}
 
.home-fragment56 {
  display: contents;
}
 
.home-text231 {
  display: inline-block;
}
 
.home-fragment57 {
  display: contents;
}
 
.home-text232 {
  display: inline-block;
}
 
@media(max-width: 1200px) {
  .home-heading {
    overflow: hidden;
    max-width: 100%;
  }
  .home-header2 {
    font-size: 40px;
  }
}
 
@media(max-width: 991px) {
  .home-hero {
    flex: 1;
    height: 0px;
  }
  .home-navbar {
    z-index: 1000;
  }
  .home-links {
    display: none;
  }
  .home-burger-menu {
    display: flex;
    padding: var(--dl-layout-space-unit);
    border-radius: var(--dl-layout-radius-round);
    background-color: #2461FF;
  }
  .home-icon1 {
    fill: white;
  }
  .home-main {
    flex-direction: column;
  }
  .home-content1 {
    padding-top: 0px;
    padding-bottom: 0px;
  }
  .home-header2 {
    max-width: 75%;
  }
  .home-caption1 {
    max-width: 75%;
  }
  .home-image2 {
    flex: 0 0 auto;
    align-items: flex-end;
    padding-right: var(--dl-layout-space-twounits);
    justify-content: flex-end;
  }
  .home-features {
    padding-top: var(--dl-layout-space-fourunits);
    flex-direction: row;
    padding-bottom: var(--dl-layout-space-fourunits);
  }
  .home-content2 {
    flex-direction: column;
  }
}
 
@media(max-width: 767px) {
  .home-navbar {
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
    padding-bottom: var(--dl-layout-space-unit);
  }
  .home-burger-menu {
    display: flex;
  }
  .home-main {
    gap: var(--dl-layout-space-threeunits);
    align-items: flex-end;
    padding-left: var(--dl-layout-space-oneandhalfunits);
    justify-content: center;
  }
  .home-header2 {
    font-size: 32px;
    max-width: 70%;
    line-height: 38px;
  }
  .home-caption1 {
    font-size: 16px;
    max-width: 70%;
    line-height: 24px;
  }
  .home-content2 {
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
  }
  .home-text108 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text109 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text112 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-caption2 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-caption3 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-caption4 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-caption5 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-caption6 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text170 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text173 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text176 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text178 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text179 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-text180 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header3 {
    font-size: 20px;
    line-height: 24px;
  }
  .home-header4 {
    font-size: 20px;
    line-height: 24px;
  }
  .home-header5 {
    font-size: 20px;
    line-height: 24px;
  }
  .home-header6 {
    font-size: 20px;
    line-height: 24px;
  }
}
 
@media(max-width: 479px) {
  .home-navbar {
    padding: var(--dl-layout-space-unit);
  }
  .home-image1 {
    width: 194px;
    height: 79px;
  }
  .home-mobile-menu {
    padding: 16px;
  }
  .home-content1 {
    padding: var(--dl-layout-space-oneandhalfunits);
  }
  .home-header2 {
    max-width: 80%;
  }
  .home-caption1 {
    max-width: 100%;
  }
  .home-book {
    width: 100%;
  }
  .home-image3 {
    max-height: 500px;
  }
}
</style>
