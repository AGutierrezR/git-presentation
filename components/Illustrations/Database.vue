<script setup lang="ts">
import { ref } from 'vue'

const props = defineProps({
  class: {
    default: '',
  },
})
</script>

<style scoped>
.st0 {
  display: none;
}
.st1 {
  display: inline;
}
.st2 {
  fill: #ffffff;
}
.st3 {
  fill: none;
  stroke: #9882ce;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st4 {
  fill: #ffffff;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st5 {
  fill: #ffffff;
  stroke: #404040;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st6 {
  fill: #b3e3ff;
  stroke: #404040;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st7 {
  fill: #b18be8;
  stroke: #404040;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st8 {
  fill: #ffffff;
  stroke: #404040;
  stroke-width: 6;
  stroke-miterlimit: 10;
}
.st9 {
  fill: #b3e3ff;
  stroke: #404040;
  stroke-width: 6;
  stroke-miterlimit: 10;
}
.st10 {
  fill: #404040;
}
.st11 {
  fill: none;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st12 {
  fill: #b18be8;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st13 {
  fill: #444444;
}
.st14 {
  fill: none;
  stroke: #404040;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st15 {
  fill: #4ed1a1;
  stroke: #404040;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st16 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 7;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st17 {
  fill: #ffffff;
  stroke: #cccccc;
  stroke-width: 7;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st18 {
  fill: none;
  stroke: #404040;
  stroke-width: 7;
  stroke-miterlimit: 10;
}
.st19 {
  fill: #b3e3ff;
  stroke: #404040;
  stroke-width: 7;
  stroke-miterlimit: 10;
}
.st20 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 8;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}
.st21 {
  fill: none;
  stroke: #404040;
  stroke-width: 8;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}
.st22 {
  fill: #ffffff;
  stroke: #404040;
  stroke-width: 4;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st23 {
  fill: #b3e3ff;
  stroke: #404040;
  stroke-width: 4;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st24 {
  fill: none;
  stroke: #cccccc;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st25 {
  fill: #999999;
}
.st26 {
  fill: #4ed1a1;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st27 {
  fill: #4cd3d6;
  stroke: #404040;
  stroke-width: 4;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st28 {
  fill: none;
  stroke: #59afe1;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st29 {
  fill: #59afe1;
  stroke: #404040;
  stroke-width: 4;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st30 {
  fill: none;
  stroke: #404040;
  stroke-width: 8;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-dasharray: 0, 30;
}
.st31 {
  fill: #ffffff;
  stroke: #59afe1;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st32 {
  fill: #fc8363;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st33 {
  fill: #cccccc;
  stroke: #404040;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st34 {
  fill: #ffffff;
  stroke: #6693ed;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st35 {
  fill: none;
  stroke: #a97cdd;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st36 {
  fill: none;
  stroke: #b3e3ff;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st37 {
  fill: none;
  stroke: #4ed1a1;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-miterlimit: 10;
}
.st38 {
  fill: none;
  stroke: #4ed1a1;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st39 {
  fill: #e24b88;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st40 {
  fill: none;
  stroke: #deeff8;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st41 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
}
.st42 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.3051;
}
.st43 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.1689;
}
.st44 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 13.9788;
}
.st45 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.7877;
}
.st46 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.9632;
}
.st47 {
  fill: #b3e3ff;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st48 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 12.543;
}
.st49 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 13.6844;
}
.st50 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 13.7717;
}
.st51 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 13.6492;
}
.st52 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 13.907;
}
.st53 {
  fill: #4cd3d6;
  stroke: #404040;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st54 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.9858;
}
.st55 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.0118;
}
.st56 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 0, 14.1243;
}
.st57 {
  fill: none;
}
.st58 {
  fill: #ffffff;
  stroke: #404040;
  stroke-width: 7;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st59 {
  fill: #59afe1;
  stroke: #404040;
  stroke-width: 7;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st60 {
  fill: #e24b88;
  stroke: #404040;
  stroke-width: 7;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st61 {
  fill: none;
  stroke: #404040;
  stroke-width: 7;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st62 {
  fill: none;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st63 {
  fill: #ffffff;
  stroke: #cccccc;
  stroke-width: 4;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st64 {
  fill: #f5f5f5;
}
.st65 {
  fill: #3873ae;
}
.st66 {
  fill: #75706c;
}
.st67 {
  fill: none;
  stroke: #b3e3ff;
  stroke-width: 4;
  stroke-miterlimit: 10;
}
.st68 {
  fill: #6f6f6f;
}
.st69 {
  fill: none;
  stroke: #6f6f6f;
  stroke-width: 2;
  stroke-miterlimit: 10;
}
.st70 {
  fill: none;
  stroke: #6f6f6f;
  stroke-width: 3;
  stroke-miterlimit: 10;
}
</style>

<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 196">
    <g id="settinguparepo">
      <path
        id="repo1_98_"
        class="st6"
        d="M348.5 135.5c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4m-126 0v27.9c0 3 1.7 5.9 4.7 8.5 9.4 8.2 32 13.9 58.3 13.9 26.4 0 48.9-5.8 58.3-13.9 3-2.6 4.7-5.5 4.7-8.5v-27.9"
      />
      <path
        class="st5"
        d="M474.5 135.5c0 12.4-28.2 22.4-63 22.4s-63-10-63-22.4c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4z"
      />
      <path
        id="repo1_97_"
        class="st6"
        d="M348.5 107.6c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4m-126 0v27.9c0 3 1.7 5.9 4.7 8.5 9.4 8.2 32 13.9 58.3 13.9 26.4 0 48.9-5.8 58.3-13.9 3-2.6 4.7-5.5 4.7-8.5v-27.9"
      />
      <path
        class="st5"
        d="M474.5 107.6c0 12.4-28.2 22.4-63 22.4s-63-10-63-22.4 28.2-22.4 63-22.4 63 10 63 22.4z"
      />
      <path
        id="repo1_96_"
        class="st6"
        d="M348.5 79.7c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4m-126 0v27.9c0 3 1.7 5.9 4.7 8.5 9.4 8.2 32 13.9 58.3 13.9 26.4 0 48.9-5.8 58.3-13.9 3-2.6 4.7-5.5 4.7-8.5v-27.9"
      />
      <path
        class="st5"
        d="M474.5 79.7c0 12.4-28.2 22.4-63 22.4s-63-10-63-22.4c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4z"
      />
      <path
        id="repo1_95_"
        class="st6"
        d="M348.5 51.8c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4m-126 0v27.9c0 3 1.7 5.9 4.7 8.5 9.4 8.2 32 13.9 58.3 13.9 26.4 0 48.9-5.8 58.3-13.9 3-2.6 4.7-5.5 4.7-8.5v-27.9"
      />
      <path
        class="st5"
        d="M474.5 51.8c0 12.4-28.2 22.4-63 22.4s-63-10-63-22.4c0-12.4 28.2-22.4 63-22.4s63 10 63 22.4z"
      />
      <path id="plus_2_" class="st11" d="M323.5 6.1v36m18-18h-36" />
    </g>
  </svg>
</template>
