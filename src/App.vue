<template>
  <div id="app">
    <adobe-toolbar>
      <adobe-btn icon="file"></adobe-btn>
      <!-- <div class="adobe adobe-btn-switch"> -->
        <span class="adobe-icon-file"></span>
      <!-- </div> -->
    </adobe-toolbar>
  </div>
</template>

<script>
import './myTstack/adobeStyle.css'

import adobeToolbar from './rvmLib/toolbar.vue'
import adobeBtn from './rvmLib/adobe-button.vue'


export default {
  name: 'app',
  components : {
    adobeToolbar,
    adobeBtn,
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>


:root {
  --fontSize: 10px;
  --fontFamily: "Adobe Clean", sans-serif;
  --colorDisabled: #393939;
  --colorFontDisabled: #525252;
  --colorFontActive: #000000;
  --colorFont: #b7b7b7;

  --colorBorder: #3e3e3e;
  --colorHover: #292929;
  --colorActive: #1f1f1f;
  --colorFocus: #46a0f5;
  --colorIcon: #b4b4b4;
  font-size: var(--fontSize);
}

body {
  background-color: #323232;
}

#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white; */
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
