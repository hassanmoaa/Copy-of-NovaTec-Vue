<template>
  <section
    :id="ourProductsId"
    class="our-products-our-products"
    v-bind:class="rootClassName"
  >
    <div class="our-products-heading1">
      <h2 class="our-products-text10">
        <slot name="heading">
          <!--Default content for heading-->
          <div class="our-products-fragment20">
            <span class="our-products-text67">Our Services</span>
          </div>
        </slot>
      </h2>
      <p class="our-products-text11">
        <slot name="text">
          <!--Default content for text-->
          <div class="our-products-fragment22">
            <p class="our-products-text80">
              <span class="our-products-text81">
                Our portfolio spans a wide range of medical specialties, ensuring
                comprehensive support for diverse clinical needs.                 
                     
              </span>
              <br class="our-products-text82" />
              <span>
                Advanced solutions to support wound healing and reduce infection
                risk.
              </span>
              <br class="our-products-text84" />
            </p>
          </div>
        </slot>
      </p>
    </div>
    <div class="our-products-content">
      <div class="our-products-grid">
        <router-link to="/">
          <div class="our-products-practice-wrapper1">
            <div id class="our-products-practice1">
              <div class="our-products-heading2">
                <h3 class="our-products-header1">
                  <slot name="header1">
                    <!--Default content for header1-->
                    <div class="our-products-fragment10">
                      <span class="our-products-text13">Physiotherapy</span>
                    </div>
                  </slot>
                </h3>
                <p class="our-products-caption10">
                  <slot name="caption1">
                    <!--Default content for caption1-->
                    <div class="our-products-fragment11">
                      <p class="our-products-caption15">
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
                      </p>
                    </div>
                  </slot>
                </p>
              </div>
              <div class="our-products-more1 read-more"></div>
            </div>
          </div>
        </router-link>
        <router-link to="/">
          <div class="our-products-practice-wrapper2">
            <div id="Practice" class="our-products-practice2">
              <div class="our-products-heading3">
                <h3 class="our-products-header2">
                  <slot name="header2">
                    <!--Default content for header2-->
                    <div class="our-products-fragment13">
                      <span class="our-products-text26">Orthopedics</span>
                    </div>
                  </slot>
                </h3>
                <p class="our-products-caption11">
                  <slot name="caption2">
                    <!--Default content for caption2-->
                    <div class="our-products-fragment19">
                      <p class="our-products-caption18">
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
                      </p>
                    </div>
                  </slot>
                </p>
              </div>
              <div class="our-products-more2 read-more"></div>
            </div>
          </div>
        </router-link>
        <router-link to="/">
          <div class="our-products-practice-wrapper3">
            <div id class="our-products-practice3">
              <div class="our-products-heading4">
                <h3 class="our-products-header3">
                  <slot name="header3">
                    <!--Default content for header3-->
                    <div class="our-products-fragment16">
                      <span class="our-products-text40">Drills</span>
                    </div>
                  </slot>
                </h3>
                <p class="our-products-caption12">
                  <slot name="caption3">
                    <!--Default content for caption3-->
                    <div class="our-products-fragment14">
                      <p class="our-products-caption16">
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
                      </p>
                    </div>
                  </slot>
                </p>
              </div>
              <div class="our-products-more3 read-more"></div>
            </div>
          </div>
        </router-link>
        <router-link to="/">
          <div class="our-products-practice-wrapper4">
            <div id class="our-products-practice4">
              <div class="our-products-heading5">
                <h3 class="our-products-header4">
                  <slot name="header4">
                    <!--Default content for header4-->
                    <div class="our-products-fragment15">
                      <span class="our-products-text39">Plasma Coblators</span>
                    </div>
                  </slot>
                </h3>
                <p class="our-products-caption13">
                  <slot name="caption4">
                    <!--Default content for caption4-->
                    <div class="our-products-fragment21">
                      <p class="our-products-caption19">
                        <span>-Arthoscopy</span>
                        <br />
                        <br class="our-products-text70" />
                        <span>-Spine</span>
                        <br />
                        <br class="our-products-text73" />
                        <span>-ENT</span>
                        <br />
                        <br class="our-products-text76" />
                        <span>-Urology</span>
                        <span class="our-products-text78">
                          <span v-html="raw52gc"></span>
                        </span>
                        <br class="our-products-text79" />
                      </p>
                    </div>
                  </slot>
                </p>
              </div>
              <div class="our-products-more4 read-more"></div>
            </div>
          </div>
        </router-link>
      </div>
      <button type="button" data-open="practices" class="button button-main">
        <span>
          <slot name="text1">
            <!--Default content for text1-->
            <div class="our-products-fragment12">
              <span class="our-products-text25">All practices</span>
            </div>
          </slot>
        </span>
      </button>
    </div>
    <div id="Practice" class="our-products-practice5">
      <div class="our-products-heading6">
        <h3 class="our-products-header5">
          <slot name="header">
            <!--Default content for header-->
            <div class="our-products-fragment17">
              <span class="our-products-text41">Endoscopy</span>
            </div>
          </slot>
        </h3>
        <p class="our-products-caption14">
          <slot name="caption">
            <!--Default content for caption-->
            <div class="our-products-fragment18">
              <p class="our-products-caption17">
                <span>-Arthoscopy</span>
                <br />
                <span>-Lapurscopy</span>
                <br />
                <span>-Urology</span>
                <br />
                <span>-ENT</span>
                <br />
                <span>-Spine</span>
              </p>
            </div>
          </slot>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'OurProducts',
  props: {
    ourProductsId: String,
    rootClassName: String,
  },
  data() {
    return {
      raw5zf4: ' ',
      raw52gc: ' ',
    }
  },
}
</script>

<style scoped>
.our-products-our-products {
  gap: var(--dl-layout-space-threeunits);
  width: 100%;
  display: flex;
  overflow: hidden;
  position: relative;
  max-width: var(--dl-layout-size-maxwidth);
  align-items: flex-start;
  padding-top: 120px;
  padding-left: var(--dl-layout-space-fiveunits);
  padding-right: 120px;
  flex-direction: row;
  padding-bottom: 120px;
}
 
.our-products-heading1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  margin-top: var(--dl-layout-space-halfunit);
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-text10 {
  font-size: 54px;
  margin-top: var(--dl-layout-space-twounits);
  margin-bottom: var(--dl-layout-space-unit);
}
 
.our-products-text11 {
  height: 276px;
  font-size: 18px;
  max-width: 385px;
  line-height: 27px;
}
 
.our-products-content {
  gap: var(--dl-layout-space-fourunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-grid {
  gap: var(--dl-layout-space-threeunits);
  flex: 1;
  display: grid;
  align-items: flex-start;
  flex-direction: column;
  grid-template-columns: repeat(2, 1fr);
}
 
.our-products-practice-wrapper1 {
  cursor: pointer;
  text-decoration: none;
}
 
.our-products-practice1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.our-products-heading2 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-header1 {
  line-height: 36px;
}
 
.our-products-caption10 {
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-more1 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
}
 
.our-products-practice-wrapper2 {
  cursor: pointer;
  text-decoration: none;
}
 
.our-products-practice2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.our-products-heading3 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-header2 {
  line-height: 36px;
}
 
.our-products-caption11 {
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-more2 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
}
 
.our-products-practice-wrapper3 {
  cursor: pointer;
  text-decoration: none;
}
 
.our-products-practice3 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.our-products-heading4 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-header3 {
  line-height: 36px;
}
 
.our-products-caption12 {
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-more3 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
}
 
.our-products-practice-wrapper4 {
  cursor: pointer;
  text-decoration: none;
}
 
.our-products-practice4 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.our-products-heading5 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-header4 {
  line-height: 36px;
}
 
.our-products-caption13 {
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-more4 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
}
 
.our-products-practice5 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.our-products-heading6 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.our-products-header5 {
  line-height: 36px;
}
 
.our-products-caption14 {
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-fragment10 {
  display: contents;
}
 
.our-products-text13 {
  display: inline-block;
}
 
.our-products-fragment11 {
  display: contents;
}
 
.our-products-caption15 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-fragment12 {
  display: contents;
}
 
.our-products-text25 {
  display: inline-block;
}
 
.our-products-fragment13 {
  display: contents;
}
 
.our-products-text26 {
  display: inline-block;
}
 
.our-products-fragment14 {
  display: contents;
}
 
.our-products-caption16 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-fragment15 {
  display: contents;
}
 
.our-products-text39 {
  display: inline-block;
}
 
.our-products-fragment16 {
  display: contents;
}
 
.our-products-text40 {
  display: inline-block;
}
 
.our-products-fragment17 {
  display: contents;
}
 
.our-products-text41 {
  display: inline-block;
}
 
.our-products-fragment18 {
  display: contents;
}
 
.our-products-caption17 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-fragment19 {
  display: contents;
}
 
.our-products-caption18 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-fragment20 {
  display: contents;
}
 
.our-products-text67 {
  display: inline-block;
}
 
.our-products-fragment21 {
  display: contents;
}
 
.our-products-caption19 {
  display: inline-block;
  max-width: 385px;
  line-height: 24px;
}
 
.our-products-fragment22 {
  display: contents;
}
 
.our-products-text80 {
  height: 276px;
  display: inline-block;
  font-size: 18px;
  max-width: 385px;
  line-height: 27px;
}
 
.our-products-text82 {
  font-size: 18px;
  line-height: 27px;
}
 

 
@media(max-width: 991px) {
  .our-products-our-products {
    flex-direction: column;
  }
  .our-productsroot-class-name {
    display: flex;
    align-items: center;
    align-content: center;
    flex-direction: column;
    justify-content: center;
  }
}
 
@media(max-width: 767px) {
  .our-products-our-products {
    padding-top: var(--dl-layout-space-fourunits);
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
    padding-bottom: var(--dl-layout-space-fourunits);
  }
  .our-products-heading1 {
    gap: var(--dl-layout-space-unit);
  }
  .our-products-text10 {
    font-size: 30px;
    line-height: 36px;
  }
  .our-products-text11 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-content {
    gap: var(--dl-layout-space-threeunits);
    width: 100%;
  }
  .our-products-grid {
    gap: var(--dl-layout-space-twounits);
    width: 100%;
    grid-template-columns: repeat(1, 1fr);
  }
  .our-products-practice1 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .our-products-header1 {
    font-size: 20px;
    line-height: 24px;
  }
  .our-products-caption10 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-practice2 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .our-products-header2 {
    font-size: 20px;
    line-height: 24px;
  }
  .our-products-caption11 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-practice3 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .our-products-header3 {
    font-size: 20px;
    line-height: 24px;
  }
  .our-products-caption12 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-practice4 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .our-products-header4 {
    font-size: 20px;
    line-height: 24px;
  }
  .our-products-caption13 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-practice5 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .our-products-header5 {
    font-size: 20px;
    line-height: 24px;
  }
  .our-products-caption14 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-caption15 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-caption16 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-caption17 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-caption18 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-caption19 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text70 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text73 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text76 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text78 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text79 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text80 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text81 {
    font-size: 14px;
    line-height: 21px;
  }
  .our-products-text84 {
    font-size: 14px;
    line-height: 21px;
  }
}
 
@media(max-width: 479px) {
  .our-productsroot-class-name {
    align-self: center;
    align-items: center;
    justify-content: center;
  }
}
</style>
