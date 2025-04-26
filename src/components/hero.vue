<template>
  <section class="hero-hero">
    <header class="hero-header1">
      <header data-thq="thq-navbar" class="hero-navbar">
        <div class="hero-left">
          <img :alt="imageAlt1" :src="imageSrc1" class="hero-image1" />
          <div class="hero-container10">
            <nav class="hero-links">
              <a href="#how-it-works" class="hero-link1">
                <slot name="text1">
                  <!--Default content for text1-->
                  <div class="hero-fragment30">
                    <span class="hero-text22">About Us</span>
                  </div>
                </slot>
              </a>
              <a href="#features" class="hero-link2">
                <slot name="link">
                  <!--Default content for link-->
                  <div class="hero-fragment34">
                    <a href="#features" class="hero-link6">
                      <span>S</span>
                      <span>ervices</span>
                    </a>
                  </div>
                </slot>
              </a>
              <span class="hero-link3">
                <slot name="link1">
                  <!--Default content for link1-->
                  <div class="hero-fragment27">
                    <span class="hero-text19">Prices</span>
                  </div>
                </slot>
              </span>
              <a href="#Footer" class="hero-link4">
                <slot name="link2">
                  <!--Default content for link2-->
                  <div class="hero-fragment25">
                    <span class="hero-text17">Contact Us</span>
                  </div>
                </slot>
              </a>
            </nav>
          </div>
        </div>
        <div data-thq="thq-burger-menu" class="hero-burger-menu">
          <svg viewBox="0 0 1024 1024" class="hero-icon1">
            <path
              d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
            ></path>
          </svg>
        </div>
        <div data-thq="thq-mobile-menu" class="hero-mobile-menu">
          <div data-thq="thq-mobile-menu-nav" data-role="Nav" class="hero-nav1">
            <div class="hero-container11">
              <img :alt="imageAlt2" :src="imageSrc2" class="hero-image2" />
              <div data-thq="thq-close-menu" class="hero-menu-close">
                <svg viewBox="0 0 1024 1024" class="hero-icon3">
                  <path
                    d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                  ></path>
                </svg>
              </div>
            </div>
            <nav
              data-thq="thq-mobile-menu-nav-links"
              data-role="Nav"
              class="hero-nav2"
            >
              <span class="hero-text10">
                <slot name="text2">
                  <!--Default content for text2-->
                  <div class="hero-fragment33">
                    <span class="hero-text25">Features</span>
                  </div>
                </slot>
              </span>
              <span class="hero-text11">
                <slot name="text3">
                  <!--Default content for text3-->
                  <div class="hero-fragment32">
                    <span class="hero-text24">How it works</span>
                  </div>
                </slot>
              </span>
              <span class="hero-text12">
                <slot name="text4">
                  <!--Default content for text4-->
                  <div class="hero-fragment24">
                    <span class="hero-text16">Prices</span>
                  </div>
                </slot>
              </span>
              <span class="hero-text13">
                <slot name="text5">
                  <!--Default content for text5-->
                  <div class="hero-fragment35">
                    <span class="hero-text28">Contact</span>
                  </div>
                </slot>
              </span>
              <button class="hero-book1 button button-main">
                <img :alt="imageAlt3" :src="imageSrc3" class="hero-image3" />
                <span class="hero-text14">
                  <slot name="text6">
                    <!--Default content for text6-->
                    <div class="hero-fragment28">
                      <span class="hero-text20">Book an appointment</span>
                    </div>
                  </slot>
                </span>
              </button>
            </nav>
          </div>
        </div>
        <div data-thq="thq-dropdown" class="hero-language-switcher list-item">
          <div
            data-thq="thq-dropdown-toggle"
            class="hero-language-switcher-toggle"
          >
            <span class="hero-language-name"><span></span></span>
            <div data-thq="thq-dropdown-arrow" class="hero-dropdown-arrow">
              <svg viewBox="0 0 1024 1024" class="hero-icon5">
                <path d="M426 726v-428l214 214z"></path>
              </svg>
            </div>
          </div>
          <ul data-thq="thq-dropdown-list" class="hero-language-switcher-list">
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment10"
              >
                <div class="hero-language-switcher-item10">
                  <a :href="languageLinkUrl">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment11"
              >
                <div class="hero-language-switcher-item11">
                  <a :href="languageLinkUrl1">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment12"
              >
                <div class="hero-language-switcher-item12">
                  <a :href="languageLinkUrl2">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment13"
              >
                <div class="hero-language-switcher-item13">
                  <a :href="languageLinkUrl3">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment14"
              >
                <div class="hero-language-switcher-item14">
                  <a :href="languageLinkUrl4">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment15"
              >
                <div class="hero-language-switcher-item15">
                  <a :href="languageLinkUrl5">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment16"
              >
                <div class="hero-language-switcher-item16">
                  <a :href="languageLinkUrl6">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment17"
              >
                <div class="hero-language-switcher-item17">
                  <a :href="languageLinkUrl7">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment18"
              >
                <div class="hero-language-switcher-item18">
                  <a :href="languageLinkUrl8">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment19"
              >
                <div class="hero-language-switcher-item19">
                  <a :href="languageLinkUrl9">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment20"
              >
                <div class="hero-language-switcher-item20">
                  <a :href="languageLinkUrl10">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment21"
              >
                <div class="hero-language-switcher-item21">
                  <a :href="languageLinkUrl11">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment22"
              >
                <div class="hero-language-switcher-item22">
                  <a :href="languageLinkUrl12">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                v-for="(all_languages, index) in locales"
                :key="index"
                class="hero-fragment23"
              >
                <div class="hero-language-switcher-item23">
                  <a :href="languageLinkUrl13">
                    Expression nodes are not supported
                  </a>
                </div>
              </div>
            </div>
          </ul>
        </div>
      </header>
    </header>
    <div class="hero-main">
      <div class="hero-content1">
        <div class="hero-heading">
          <h1 class="hero-header2">
            <slot name="header">
              <!--Default content for header-->
              <div class="hero-fragment29">
                <span class="hero-text21">
                  Experienced general practitioners who have an eye for your care
                </span>
              </div>
            </slot>
          </h1>
          <p class="hero-caption">
            <slot name="caption">
              <!--Default content for caption-->
              <div class="hero-fragment26">
                <span class="hero-text18">
                  We are a leading provider of advanced medical solutions
                  dedicated to improving patient care and enhancing recovery.
                  <span v-html="rawthf8"></span>
                </span>
              </div>
            </slot>
          </p>
        </div>
        <button class="button button-main hero-book2">
          <span>
            <slot name="text">
              <!--Default content for text-->
              <div class="hero-fragment31">
                <span class="hero-text23">Our Products --&gt;</span>
              </div>
            </slot>
          </span>
        </button>
      </div>
      <div class="hero-image4">
        <img :alt="imageAlt" :src="imageSrc" class="hero-image5" />
      </div>
    </div>
    <div id="features" class="hero-features">
      <div class="hero-content2">
        <a href="#Our Products" class="hero-link5">
          <app-features title="Services" class="hero-component1"></app-features>
        </a>
        <app-features title=" Trainings"></app-features>
        <app-features
          title=" Innovations"
          description="Lorem ipsum dolor sit amet, consectetur adipiscing elit."
        ></app-features>
      </div>
    </div>
    <app-background rootClassName="backgroundroot-class-name"></app-background>
  </section>
</template>

<script>
import AppFeatures from './features'
import AppBackground from './background'

export default {
  name: 'Hero',
  props: {
    languageLinkUrl: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    imageAlt: {
      type: String,
      default: 'image',
    },
    imageSrc1: {
      type: String,
      default: '/nova_tec-200h.jpg',
    },
    imageSrc3: {
      type: String,
      default: '/Icons/calendar.svg',
    },
    languageLinkUrl4: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl11: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl10: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl13: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl7: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl6: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    imageAlt1: {
      type: String,
      default: 'image',
    },
    imageSrc2: {
      type: String,
      default: '/Branding/logo-1500h.png',
    },
    imageAlt3: {
      type: String,
      default: 'image',
    },
    languageLinkUrl5: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl1: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl8: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl12: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl9: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    languageLinkUrl2: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    imageSrc: {
      type: String,
      default: '/doctor-image-1400w.png',
    },
    languageLinkUrl3: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    imageAlt2: {
      type: String,
      default: 'image',
    },
  },
  components: {
    AppFeatures,
    AppBackground,
  },
  data() {
    return {
      raw5ihv: ' ',
      rawthf8: ' ',
    }
  },
}
</script>

<style scoped>
.hero-hero {
  width: 100%;
  height: 100vh;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
 
.hero-header1 {
  width: 100%;
  display: flex;
  justify-content: center;
}
 
.hero-navbar {
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
 
.hero-left {
  gap: var(--dl-layout-space-twounits);
  display: flex;
  align-items: center;
  margin-right: 29px;
  justify-content: center;
}
 
.hero-image1 {
  width: 296px;
  height: 86px;
  object-fit: cover;
}
 
.hero-container10 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.hero-links {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-items: center;
  justify-content: center;
}
 
.hero-link1 {
  color: #ffffff;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
 
.hero-link2 {
  color: #ffffff;
  cursor: pointer;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
  text-decoration: none;
}
 
.hero-link2:hover {
  opacity: 0.5;
}
 
.hero-link3 {
  color: #ffffff;
  cursor: pointer;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
}
 
.hero-link3:hover {
  opacity: 0.5;
}
 
.hero-link4 {
  color: #ffffff;
  cursor: pointer;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
  text-decoration: none;
}
 
.hero-link4:hover {
  opacity: 0.5;
}
 
.hero-burger-menu {
  display: none;
  align-items: center;
  justify-content: center;
}
 
.hero-icon1 {
  width: var(--dl-layout-size-xsmall);
  height: var(--dl-layout-size-xsmall);
}
 
.hero-mobile-menu {
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
 
.hero-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.hero-container11 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-layout-space-threeunits);
  justify-content: space-between;
}
 
.hero-image2 {
  height: 2rem;
}
 
.hero-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
 
.hero-icon3 {
  width: var(--dl-layout-size-xsmall);
  height: var(--dl-layout-size-xsmall);
}
 
.hero-nav2 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.hero-text10 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.hero-text11 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.hero-text12 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.hero-text13 {
  margin-bottom: var(--dl-layout-space-unit);
}
 
.hero-book1 {
  text-decoration: none;
}
 
.hero-image3 {
  width: 18px;
  object-fit: cover;
}
 
.hero-text14 {
  font-family: Inter;
}
 
.hero-language-switcher {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-layout-radius-radius2);
}
 
.hero-language-switcher-toggle {
  fill: #595959;
  color: #ffffff;
  width: 100%;
  display: inline-flex;
  align-items: center;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  border-radius: var(--dl-layout-radius-radius2);
  padding-right: var(--dl-layout-space-unit);
  padding-bottom: var(--dl-layout-space-halfunit);
}
 
.hero-language-name {
  font-size: 14px;
  font-style: normal;
  text-align: center;
  font-weight: 500;
  margin-right: 4px;
  vertical-align: middle;
}
 
.hero-dropdown-arrow {
  transition: 0.3s;
}
 
.hero-icon5 {
  fill: #ffffff;
  width: 18px;
  height: 18px;
  transition: 0.3s;
}
 
.hero-language-switcher-list {
  left: 0%;
  width: max-content;
  display: none;
  z-index: 100;
  position: absolute;
  min-width: 100%;
  transition: 0.3s;
  align-items: stretch;
  border-color: #D9D9D9;
  border-width: 1px;
  border-radius: var(--dl-layout-radius-radius4);
  flex-direction: column;
  list-style-type: none;
  list-style-position: inside;
}
 
.hero-fragment10 {
  display: contents;
}
 
.hero-language-switcher-item10 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment11 {
  display: contents;
}
 
.hero-language-switcher-item11 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment12 {
  display: contents;
}
 
.hero-language-switcher-item12 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment13 {
  display: contents;
}
 
.hero-language-switcher-item13 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment14 {
  display: contents;
}
 
.hero-language-switcher-item14 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment15 {
  display: contents;
}
 
.hero-language-switcher-item15 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment16 {
  display: contents;
}
 
.hero-language-switcher-item16 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment17 {
  display: contents;
}
 
.hero-language-switcher-item17 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment18 {
  display: contents;
}
 
.hero-language-switcher-item18 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment19 {
  display: contents;
}
 
.hero-language-switcher-item19 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment20 {
  display: contents;
}
 
.hero-language-switcher-item20 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment21 {
  display: contents;
}
 
.hero-language-switcher-item21 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment22 {
  display: contents;
}
 
.hero-language-switcher-item22 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-fragment23 {
  display: contents;
}
 
.hero-language-switcher-item23 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  padding-right: var(--dl-layout-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-halfunit);
  background-color: #fff;
}
 
.hero-main {
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
 
.hero-content1 {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-oneandhalfunits);
  justify-content: center;
}
 
.hero-heading {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.hero-header2 {
  color: #ffffff;
  width: 100%;
  font-size: 62px;
  max-width: 750px;
  font-style: normal;
  font-weight: 600;
  line-height: 74px;
}
 
.hero-caption {
  color: rgb(255, 255, 255);
  width: 100%;
  font-size: 18px;
  max-width: 600px;
  line-height: 27px;
}
 
.hero-image4 {
  flex: 1;
  display: flex;
  overflow: hidden;
  max-width: 100%;
  align-items: flex-end;
  padding-right: var(--dl-layout-space-fiveunits);
  flex-direction: row;
  justify-content: center;
}
 
.hero-image5 {
  height: 95%;
  object-fit: cover;
}
 
.hero-features {
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
 
.hero-content2 {
  gap: var(--dl-layout-space-threeunits);
  flex: 1;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-left: var(--dl-layout-space-fiveunits);
  padding-right: var(--dl-layout-space-fiveunits);
  flex-direction: row;
}
 
.hero-link5 {
  display: contents;
}
 
.hero-component1 {
  text-decoration: none;
}
 
.hero-fragment24 {
  display: contents;
}
 
.hero-text16 {
  display: inline-block;
}
 
.hero-fragment25 {
  display: contents;
}
 
.hero-text17 {
  display: inline-block;
}
 
.hero-fragment26 {
  display: contents;
}
 
.hero-text18 {
  display: inline-block;
}
 
.hero-fragment27 {
  display: contents;
}
 
.hero-text19 {
  display: inline-block;
}
 
.hero-fragment28 {
  display: contents;
}
 
.hero-text20 {
  display: inline-block;
}
 
.hero-fragment29 {
  display: contents;
}
 
.hero-text21 {
  display: inline-block;
}
 
.hero-fragment30 {
  display: contents;
}
 
.hero-text22 {
  display: inline-block;
}
 
.hero-fragment31 {
  display: contents;
}
 
.hero-text23 {
  display: inline-block;
}
 
.hero-fragment32 {
  display: contents;
}
 
.hero-text24 {
  display: inline-block;
}
 
.hero-fragment33 {
  display: contents;
}
 
.hero-text25 {
  display: inline-block;
}
 
.hero-fragment34 {
  display: contents;
}
 
.hero-link6 {
  color: #ffffff;
  cursor: pointer;
  display: inline-block;
  font-size: 20px;
  font-style: normal;
  transition: 0.3s;
  font-weight: 500;
  line-height: 24px;
  text-decoration: none;
}
 
.hero-link6:hover {
  opacity: 0.5;
}
 
.hero-fragment35 {
  display: contents;
}
 
.hero-text28 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .hero-hero {
    flex: 1;
    height: 0px;
  }
  .hero-navbar {
    z-index: 1000;
  }
  .hero-links {
    display: none;
  }
  .hero-burger-menu {
    display: flex;
    padding: var(--dl-layout-space-unit);
    border-radius: var(--dl-layout-radius-round);
    background-color: #2461FF;
  }
  .hero-icon1 {
    fill: white;
  }
  .hero-main {
    flex-direction: column;
  }
  .hero-content1 {
    padding-top: 0px;
    padding-bottom: 0px;
  }
  .hero-header2 {
    max-width: 75%;
  }
  .hero-caption {
    max-width: 75%;
  }
  .hero-image4 {
    flex: 0 0 auto;
    align-items: flex-end;
    padding-right: var(--dl-layout-space-twounits);
    justify-content: flex-end;
  }
  .hero-features {
    padding-top: var(--dl-layout-space-fourunits);
    flex-direction: row;
    padding-bottom: var(--dl-layout-space-fourunits);
  }
  .hero-content2 {
    flex-direction: column;
  }
}
 
@media(max-width: 767px) {
  .hero-navbar {
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
    padding-bottom: var(--dl-layout-space-unit);
  }
  .hero-burger-menu {
    display: flex;
  }
  .hero-main {
    gap: var(--dl-layout-space-threeunits);
    align-items: flex-end;
    padding-left: var(--dl-layout-space-oneandhalfunits);
    justify-content: center;
  }
  .hero-header2 {
    font-size: 32px;
    max-width: 70%;
    line-height: 38px;
  }
  .hero-caption {
    font-size: 16px;
    max-width: 70%;
    line-height: 24px;
  }
  .hero-content2 {
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
  }
}
 
@media(max-width: 479px) {
  .hero-navbar {
    padding: var(--dl-layout-space-unit);
  }
  .hero-mobile-menu {
    padding: 16px;
  }
  .hero-content1 {
    padding: var(--dl-layout-space-oneandhalfunits);
  }
  .hero-header2 {
    max-width: 80%;
  }
  .hero-caption {
    max-width: 100%;
  }
  .hero-book2 {
    width: 100%;
  }
  .hero-image5 {
    max-height: 500px;
  }
}
</style>
