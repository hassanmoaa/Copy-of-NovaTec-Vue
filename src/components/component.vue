<template>
  <div id="manuCont" class="component-container">
    <h1 class="component-text1">
      <slot name="heading">
        <!--Default content for heading-->
        <div class="component-fragment">
          <span class="component-text2">Our Manufacture</span>
        </div>
      </slot>
    </h1>
    <div
      data-thq="slider"
      data-autoplay="true"
      data-navigation="true"
      data-pagination="true"
      class="component-slider swiper"
    >
      <div
        data-thq="slider-wrapper"
        class="swiper-wrapper component-slider-wrapper"
      >
        <div
          data-thq="slider-slide"
          class="component-slider-slide10 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide11 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide12 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide13 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide14 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide15 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide16 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide17 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide18 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide19 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide20 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide21 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide22 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide23 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide24 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide25 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide26 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide27 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide28 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide29 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide30 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide31 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide32 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide33 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide34 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide35 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="component-slider-slide36 swiper-slide"
        ></div>
      </div>
      <div
        data-thq="slider-pagination"
        class="component-slider-pagination swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
      >
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet swiper-pagination-bullet-active"
        ></div>
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet"
        ></div>
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet"
        ></div>
      </div>
      <div data-thq="slider-button-prev" class="swiper-button-prev"></div>
      <div data-thq="slider-button-next" class="swiper-button-next"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {},
}
</script>

<style scoped>
.component-container {
  flex: 0 0 auto;
  display: flex;
  padding: var(--dl-layout-space-halfunit);
  position: relative;
  max-width: 100%;
  align-self: center;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
 
.component-text1 {
  color: var(--dl-color-gray-black);
  display: flex;
  font-size: 56px;
  align-self: flex-start;
  text-align: left;
  font-family: "Poppins";
  padding-top: var(--dl-layout-space-oneandhalfunits);
  padding-bottom: var(--dl-layout-space-oneandhalfunits);
}
 
.component-slider {
  width: 1600px;
  height: 674px;
  display: inline-block;
  overflow: hidden;
  max-width: 100%;
}
 
.component-slider-slide10 {
  height: 679px;
  display: flex;
  align-items: center;
  background-size: 100%;
  justify-content: center;
  background-image: url("/Manufacture/img-20250406-wa0004-700h.jpg");
}
 
.component-slider-slide11 {
  height: 684px;
  display: flex;
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0005-700h.jpg");
}
 
.component-slider-slide12 {
  height: 780px;
  display: flex;
  padding-bottom: 52px;
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0006-800h.jpg");
}
 
.component-slider-slide13 {
  height: 780px;
  display: flex;
  padding-bottom: 52px;
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0007-800h.jpg");
}
 
.component-slider-slide14 {
  height: 674px;
  display: flex;
  padding-bottom: 52px;
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0008-700h.jpg");
}
 
.component-slider-slide15 {
  height: 679px;
  display: flex;
  padding-bottom: 52px;
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0009-700h.jpg");
}
 
.component-slider-slide16 {
  height: 669px;
  display: flex;
  padding-bottom: 52px;
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0010-700h.jpg");
}
 
.component-slider-slide17 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0011-700h.jpg");
}
 
.component-slider-slide18 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0012-700h.jpg");
}
 
.component-slider-slide19 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0013-700h.jpg");
}
 
.component-slider-slide20 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0014-700h.jpg");
}
 
.component-slider-slide21 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0015-700h.jpg");
}
 
.component-slider-slide22 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0016-700h.jpg");
}
 
.component-slider-slide23 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0017-700h.jpg");
}
 
.component-slider-slide24 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0018-700h.jpg");
}
 
.component-slider-slide25 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0019-1500w.jpg");
}
 
.component-slider-slide26 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0020-700h.jpg");
}
 
.component-slider-slide27 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0021-700h.jpg");
}
 
.component-slider-slide28 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0023-700h.jpg");
}
 
.component-slider-slide29 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0024-700h.jpg");
}
 
.component-slider-slide30 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0025-700h.jpg");
}
 
.component-slider-slide31 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0026-700h.jpg");
}
 
.component-slider-slide32 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0027-700h.jpg");
}
 
.component-slider-slide33 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0028-700h.jpg");
}
 
.component-slider-slide34 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0029-700h.jpg");
}
 
.component-slider-slide35 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0030-700h.jpg");
}
 
.component-slider-slide36 {
  height: 675px;
  display: flex;
  padding-bottom: var(--dl-layout-space-threeunits);
  background-size: 100%;
  background-image: url("/Manufacture/img-20250406-wa0031-700h.jpg");
}
 
.component-slider-pagination {
  display: block;
}
 
.component-fragment {
  display: contents;
}
 
.component-text2 {
  display: inline-block;
}
 
@media(max-width: 479px) {
  .component-container {
    width: 100%;
    margin: auto;
    padding: 5%;
    overflow: hidden;
    max-width: 100%;
    box-sizing: border-box;
    align-items: center;
    flex-direction: column;
  }
  .component-text1 {
    font-size: large;
  }
  .component-slider {
    height: auto;
  }
  .component-slider-wrapper {
    overflow-x: auto;
    flex-direction: row;
    scroll-behavior: smooth;
    scroll-snap-type: x;
  }
}
</style>
