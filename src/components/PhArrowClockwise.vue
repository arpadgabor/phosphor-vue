/* GENERATED FILE */
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 256 256"
    :width="displaySize"
    :height="displaySize"
    :fill="displayColor"
    :transform="displayMirrored"
    v-bind="$attrs"
    v-on="$listeners"
  >
    <slot />
    <g v-if="displayWeight === 'bold'">
      <polyline
        points="176.167 99.716 224.167 99.716 224.167 51.716"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M190.2254,190.2254a88,88,0,1,1,0-124.4508l33.94112,33.94113"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <polyline
        points="176.167 99.716 224.167 99.716 224.167 51.716"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M190.2254,190.2254a88,88,0,1,1,0-124.4508l33.94112,33.94113"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M225.33447,107.62115c.13135-.01928.26319-.03424.39356-.06005.14038-.02777.27661-.0661.4143-.10114.115-.02923.23072-.05426.34449-.08862.13427-.04059.26367-.0907.39477-.13806.11524-.04151.2312-.07929.345-.12629.12085-.05011.23682-.10876.35449-.16455.11915-.05621.23926-.10907.356-.17144.11133-.0597.21729-.12757.32544-.1922.116-.06928.2334-.13483.34644-.21051.11718-.07831.22729-.16553.33984-.24976.09644-.07227.19556-.1394.28955-.21655.18628-.1529.36426-.31531.53589-.48413.01611-.01593.03394-.02918.05-.04529.02051-.02051.0376-.04321.05762-.06391.16357-.16711.32177-.33941.47045-.52032.08277-.10059.15479-.20648.23194-.31006.07861-.10571.1604-.20862.23389-.3183.08081-.12072.15112-.24591.22485-.36993.05932-.1.12231-.19757.17749-.30035.06738-.12592.12475-.25531.18481-.384.05078-.1084.10523-.21466.15137-.32568.05151-.12463.09326-.25189.13843-.37848.04272-.11987.08911-.238.12622-.36047.03857-.12775.06714-.25757.09936-.38678.03077-.124.06568-.24622.09082-.37244.03-.15088.04834-.30328.06958-.45544.01465-.10645.03541-.21094.0459-.31867a7.97366,7.97366,0,0,0,.04-.79706V51.71582a8,8,0,0,0-16,0v28.686L195.88281,60.11768a95.9551,95.9551,0,1,0,0,135.76464,8.00018,8.00018,0,1,0-11.31445-11.31347,80.00009,80.00009,0,1,1,0-113.1377L204.853,91.71582H176.167a8,8,0,0,0,0,16h48c.02979,0,.0586-.00415.08838-.00446.23316-.00256.46631-.01245.69824-.03527C225.08252,107.66351,225.20752,107.63977,225.33447,107.62115Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <polyline
        points="176.167 99.716 224.167 99.716 224.167 51.716"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M190.2254,190.2254a88,88,0,1,1,0-124.4508l33.94112,33.94113"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <polyline
        points="176.167 99.716 224.167 99.716 224.167 51.716"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M190.2254,190.2254a88,88,0,1,1,0-124.4508l33.94112,33.94113"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <polyline
        points="176.167 99.716 224.167 99.716 224.167 51.716"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M190.2254,190.2254a88,88,0,1,1,0-124.4508l33.94112,33.94113"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
  </svg>
</template>

<script lang="ts">
import Vue from "vue";
import {
  IconComputed,
  IconProps,
  PropValidator,
  IconContext,
  ContextGetter
} from "@/lib/types";
export default Vue.extend<{}, {}, IconComputed, IconProps>({
  name: "PhArrowClockwise",
  props: PropValidator,
  inject: ContextGetter,
  computed: {
    displayWeight() {
      const { weight, contextWeight } = this as IconProps & IconContext;
      return weight ?? contextWeight;
    },
    displaySize() {
      const { size, contextSize } = this as IconProps & IconContext;
      return size ?? contextSize;
    },
    displayColor() {
      const { color, contextColor } = this as IconProps & IconContext;
      return color ?? contextColor;
    },
    displayMirrored() {
      const { mirrored, contextMirrored } = this as IconProps & IconContext;
      return mirrored ?? contextMirrored ? "scale(-1, 1)" : undefined;
    }
  }
});
</script>
