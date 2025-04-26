<template>
  <div class="background-background" v-bind:class="rootClassName"></div>
</template>

<script>
export default {
  name: 'Background',
  props: {
    rootClassName: String,
  },
}
</script>

<style scoped>
.background-background {
  width: 100%;
  height: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
  background-color: #334a53;
}
 
.backgroundroot-class-name {
  right: 0px;
  bottom: 0px;
  position: absolute;
}
 
.backgroundroot-class-name1 {
  right: 0px;
  bottom: 0px;
  position: absolute;
}
 
@media(max-width: 991px) {
  .background-background {
    left: 0px;
    width: 100%;
    bottom: 0px;
    height: 55%;
    position: absolute;
    justify-content: flex-end;
  }
}
</style>
