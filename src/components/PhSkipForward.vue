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
      <path
        d="M188.82976,121.17374,68.1716,47.4382A8,8,0,0,0,56,54.26445v147.4711a8,8,0,0,0,12.1716,6.82625l120.65816-73.73555A8,8,0,0,0,188.82976,121.17374Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="200"
        y1="40"
        x2="200"
        y2="216"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M188.82976,121.17374,68.1716,47.4382A8,8,0,0,0,56,54.26445v147.4711a8,8,0,0,0,12.1716,6.82625l120.65816-73.73555A8,8,0,0,0,188.82976,121.17374Z"
        opacity="0.2"
      />
      <path
        d="M188.82976,121.17374,68.1716,47.4382A8,8,0,0,0,56,54.26445v147.4711a8,8,0,0,0,12.1716,6.82625l120.65816-73.73555A8,8,0,0,0,188.82976,121.17374Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="200"
        y1="40"
        x2="200"
        y2="216"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M208,40V216a8,8,0,0,1-16,0V142.26416l-119.65625,73.124A16.00029,16.00029,0,0,1,48,201.73535V54.26465A16.0002,16.0002,0,0,1,72.34277,40.61133L192,113.73535V40a8,8,0,0,1,16,0Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M188.82976,121.17374,68.1716,47.4382A8,8,0,0,0,56,54.26445v147.4711a8,8,0,0,0,12.1716,6.82625l120.65816-73.73555A8,8,0,0,0,188.82976,121.17374Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="200"
        y1="40"
        x2="200"
        y2="216"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M188.82976,121.17374,68.1716,47.4382A8,8,0,0,0,56,54.26445v147.4711a8,8,0,0,0,12.1716,6.82625l120.65816-73.73555A8,8,0,0,0,188.82976,121.17374Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="200"
        y1="40"
        x2="200"
        y2="216"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M188.82976,121.17374,68.1716,47.4382A8,8,0,0,0,56,54.26445v147.4711a8,8,0,0,0,12.1716,6.82625l120.65816-73.73555A8,8,0,0,0,188.82976,121.17374Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="200"
        y1="40"
        x2="200"
        y2="216"
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
  name: "PhSkipForward",
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
