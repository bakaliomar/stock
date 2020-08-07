<template>
  <div class="container">
    <app-header></app-header>
    <router-view></router-view>
  </div>
</template>
<script lang='ts'>
import Vue from 'vue'
import { Component } from 'vue-property-decorator'
import Header from '@/components/Header.vue'
@Component({
  // Specify `components` option.
  // See Vue.js docs for all available options:
  // https://vuejs.org/v2/api/#Options-Data
  components: {
    // eslint-disable-next-line
    appHeader : Header
  }
})
export default class Home extends Vue {
  
}
</script>
<style lang="scss">
</style>
