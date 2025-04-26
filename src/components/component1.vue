<template>
  <div class="component1-container">
    <section class="component1-scientific">
      <div class="component1-heading10">
        <h2 class="component1-text10">
          <slot name="heading">
            <!--Default content for heading-->
            <div class="component1-fragment10">
              <span class="component1-text12">Scientific Life</span>
            </div>
          </slot>
        </h2>
        <p class="component1-text11">
          <slot name="text">
            <!--Default content for text-->
            <div class="component1-fragment12">
              <p class="component1-text15">
                <span>• Scientific Activities</span>
                <br />
                <span>• Training</span>
                <br />
                <span>• Services</span>
                <br />
                <span>• Innovations</span>
                <br />
                <br />
              </p>
            </div>
          </slot>
        </p>
      </div>
      <div class="component1-content">
        <div class="component1-grid">
          <router-link to="/" class="component1-navlink1">
            <div class="component1-practice-wrapper1">
              <div id class="component1-practice1">
                <div class="component1-heading11">
                  <h3 class="component1-header10">
                    <slot name="header">
                      <!--Default content for header-->
                      <div class="component1-fragment20">
                        <h3 class="component1-header22">
                          <span><span v-html="raw7w3b"></span></span>
                          <span class="component1-text35">
                            1. Research / Scientific Activities / Training
                          </span>
                          <br />
                        </h3>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink2">
            <div class="component1-practice-wrapper2">
              <div id="Practice" class="component1-practice2">
                <div class="component1-heading12">
                  <h3 class="component1-header11">
                    <slot name="header1">
                      <!--Default content for header1-->
                      <div class="component1-fragment19">
                        <h3 class="component1-header21">
                          <span class="component1-text32">
                            2. Supervision &amp; Tracing of new products &amp;
                            implements
                          </span>
                          <br />
                        </h3>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink3">
            <div class="component1-practice-wrapper3">
              <div id class="component1-practice3">
                <div class="component1-heading13">
                  <h3 class="component1-header12">
                    <slot name="header2">
                      <!--Default content for header2-->
                      <div class="component1-fragment18">
                        <h3 class="component1-header20">
                          <span class="component1-text30">
                            3. Engineering, Maintenance (of Equipment), Programmes
                          </span>
                          <br />
                        </h3>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink4">
            <div class="component1-practice-wrapper4">
              <div id="Practice" class="component1-practice4">
                <div class="component1-heading14">
                  <h3 class="component1-header13">
                    <slot name="header3">
                      <!--Default content for header3-->
                      <div class="component1-fragment11">
                        <h3 class="component1-header19">
                          <span class="component1-text13">
                            4. Teamwork / Follow-up
                          </span>
                          <br />
                        </h3>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
              <div id class="component1-practice5">
                <div class="component1-heading15">
                  <h3 class="component1-header14">
                    <slot name="header4">
                      <!--Default content for header4-->
                      <div class="component1-fragment17">
                        <span class="component1-text29">
                          5. Customers Training &amp; Upgrading
                        </span>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink5">
            <div class="component1-practice-wrapper5">
              <div id class="component1-practice6">
                <div class="component1-heading16">
                  <h3 class="component1-header15">
                    <slot name="header5">
                      <!--Default content for header5-->
                      <div class="component1-fragment16">
                        <span class="component1-text28">
                          6. Scientific Groups, Societies, and Activities
                        </span>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink6">
            <div class="component1-practice-wrapper6">
              <div id class="component1-practice7">
                <div class="component1-heading17">
                  <h3 class="component1-header16">
                    <slot name="header6">
                      <!--Default content for header6-->
                      <div class="component1-fragment15">
                        <span class="component1-text27">
                          7. Share Experiences Internationally
                        </span>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink7">
            <div class="component1-practice-wrapper7">
              <div id class="component1-practice8">
                <div class="component1-heading18">
                  <h3 class="component1-header17">
                    <slot name="header7">
                      <!--Default content for header7-->
                      <div class="component1-fragment14">
                        <span class="component1-text26">
                          8. Clinical Groups for More Achievement, More
                          Operations, and More Research Papers
                        </span>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
          <router-link to="/" class="component1-navlink8">
            <div class="component1-practice-wrapper8">
              <div id class="component1-practice9">
                <div class="component1-heading19">
                  <h3 class="component1-header18">
                    <slot name="header8">
                      <!--Default content for header8-->
                      <div class="component1-fragment13">
                        <span class="component1-text25">
                          9. Our Scientific Sheets
                        </span>
                      </div>
                    </slot>
                  </h3>
                </div>
              </div>
            </div>
          </router-link>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Component1',
  props: {},
  data() {
    return {
      rawo3m4: ' ',
      raw7w3b: ' ',
    }
  },
}
</script>

<style scoped>
.component1-container {
  width: 100%;
  height: 976px;
  display: flex;
  position: relative;
  align-self: center;
  justify-content: center;
}
 
.component1-scientific {
  gap: var(--dl-layout-space-threeunits);
  width: 1431px;
  cursor: auto;
  height: 100%;
  display: flex;
  overflow: hidden;
  max-width: var(--dl-layout-size-maxwidth);
  align-items: flex-start;
  padding-top: var(--dl-layout-space-sixunits);
  padding-left: var(--dl-layout-space-fiveunits);
  padding-right: 120px;
  flex-direction: row;
  padding-bottom: var(--dl-layout-space-sixunits);
  justify-content: center;
}
 
.component1-heading10 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  margin-top: var(--dl-layout-space-halfunit);
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-text10 {
  font-size: 54px;
  margin-top: var(--dl-layout-space-twounits);
  margin-bottom: var(--dl-layout-space-unit);
}
 
.component1-text11 {
  height: 276px;
  font-size: 18px;
  max-width: 385px;
  line-height: 27px;
}
 
.component1-content {
  gap: var(--dl-layout-space-fourunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-grid {
  width: 718px;
  height: 605px;
  display: flex;
  flex-direction: column;
}
 
.component1-navlink1 {
  display: contents;
}
 
.component1-practice-wrapper1 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading11 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header10 {
  width: 240px;
  line-height: 36px;
}
 
.component1-navlink2 {
  display: contents;
}
 
.component1-practice-wrapper2 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading12 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header11 {
  line-height: 36px;
}
 
.component1-navlink3 {
  display: contents;
}
 
.component1-practice-wrapper3 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice3 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading13 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header12 {
  line-height: 36px;
}
 
.component1-navlink4 {
  display: contents;
}
 
.component1-practice-wrapper4 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice4 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading14 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header13 {
  line-height: 36px;
}
 
.component1-practice5 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading15 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header14 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
  line-height: 36px;
}
 
.component1-navlink5 {
  display: contents;
}
 
.component1-practice-wrapper5 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice6 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading16 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header15 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
  line-height: 36px;
}
 
.component1-navlink6 {
  display: contents;
}
 
.component1-practice-wrapper6 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice7 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading17 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header16 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
  line-height: 36px;
}
 
.component1-navlink7 {
  display: contents;
}
 
.component1-practice-wrapper7 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice8 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading18 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header17 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
  line-height: 36px;
}
 
.component1-navlink8 {
  display: contents;
}
 
.component1-practice-wrapper8 {
  cursor: pointer;
  text-decoration: none;
}
 
.component1-practice9 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-threeunits);
  border-color: #B4B9C6;
  flex-direction: column;
  border-top-width: 1px;
}
 
.component1-heading19 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.component1-header18 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
  line-height: 36px;
}
 
.component1-fragment10 {
  display: contents;
}
 
.component1-text12 {
  display: inline-block;
}
 
.component1-fragment11 {
  display: contents;
}
 
.component1-header19 {
  display: inline-block;
  line-height: 36px;
}
 
.component1-text13 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.component1-fragment12 {
  display: contents;
}
 
.component1-text15 {
  height: 276px;
  display: inline-block;
  font-size: 18px;
  max-width: 385px;
  line-height: 27px;
}
 
.component1-fragment13 {
  display: contents;
}
 
.component1-text25 {
  display: inline-block;
}
 
.component1-fragment14 {
  display: contents;
}
 
.component1-text26 {
  display: inline-block;
}
 
.component1-fragment15 {
  display: contents;
}
 
.component1-text27 {
  display: inline-block;
}
 
.component1-fragment16 {
  display: contents;
}
 
.component1-text28 {
  display: inline-block;
}
 
.component1-fragment17 {
  display: contents;
}
 
.component1-text29 {
  display: inline-block;
}
 
.component1-fragment18 {
  display: contents;
}
 
.component1-header20 {
  display: inline-block;
  line-height: 36px;
}
 
.component1-text30 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.component1-fragment19 {
  display: contents;
}
 
.component1-header21 {
  display: inline-block;
  line-height: 36px;
}
 
.component1-text32 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
.component1-fragment20 {
  display: contents;
}
 
.component1-header22 {
  width: 240px;
  display: inline-block;
  line-height: 36px;
}
 
.component1-text35 {
  font-size: 19px;
  font-style: normal;
  font-weight: 500;
}
 
@media(max-width: 991px) {
  .component1-scientific {
    height: 100%;
    padding: var(--dl-layout-space-twounits);
    overflow: hidden;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .component1-heading10 {
    height: 224px;
    padding-bottom: 0px;
  }
}
 
@media(max-width: 767px) {
  .component1-scientific {
    align-items: center;
    padding-top: var(--dl-layout-space-fourunits);
    padding-left: var(--dl-layout-space-oneandhalfunits);
    padding-right: var(--dl-layout-space-oneandhalfunits);
    padding-bottom: var(--dl-layout-space-fourunits);
  }
  .component1-heading10 {
    gap: var(--dl-layout-space-unit);
  }
  .component1-text10 {
    font-size: 30px;
    line-height: 36px;
  }
  .component1-text11 {
    font-size: 14px;
    line-height: 21px;
  }
  .component1-content {
    gap: var(--dl-layout-space-threeunits);
    width: 100%;
  }
  .component1-grid {
    gap: var(--dl-layout-space-twounits);
    width: 100%;
    grid-template-columns: repeat(1, 1fr);
  }
  .component1-practice1 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header10 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice2 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header11 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice3 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header12 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice4 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header13 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice5 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header14 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice6 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header15 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice7 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header16 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice8 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header17 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-practice9 {
    padding-top: var(--dl-layout-space-oneandhalfunits);
  }
  .component1-header18 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-header19 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-text15 {
    font-size: 14px;
    line-height: 21px;
  }
  .component1-header20 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-header21 {
    font-size: 20px;
    line-height: 24px;
  }
  .component1-header22 {
    font-size: 20px;
    line-height: 24px;
  }
}
 
@media(max-width: 479px) {
  .component1-heading10 {
    height: 226px;
    margin: var(--dl-layout-space-halfunit);
  }
}
</style>
