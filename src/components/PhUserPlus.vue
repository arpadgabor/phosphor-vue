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
      <line
        x1="176"
        y1="56"
        x2="224"
        y2="56"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="200"
        y1="32"
        x2="200"
        y2="80"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M30.989,215.99064a112.03731,112.03731,0,0,1,194.02311.002"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M188.05124,118.18275a63.96647,63.96647,0,1,1-45.27249-84.46794"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <circle cx="128" cy="96" r="64" opacity="0.2" />
      <line
        x1="176"
        y1="56"
        x2="224"
        y2="56"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="200"
        y1="32"
        x2="200"
        y2="80"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M30.989,215.99064a112.03731,112.03731,0,0,1,194.02311.002"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M188.05124,118.18275a63.96647,63.96647,0,1,1-45.27249-84.46794"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <g>
        <path
          d="M176,64h16V80a8,8,0,0,0,16,0V64h16a8,8,0,0,0,0-16H208V32a8,8,0,0,0-16,0V48H176a8,8,0,0,0,0,16Z"
        />
        <path
          d="M231.93652,211.98633a120.48718,120.48718,0,0,0-67.12-54.14258,72.111,72.111,0,0,0,34.73474-53.85516A24.02341,24.02341,0,0,1,176,80a23.99523,23.99523,0,0,1-10.62024-45.51459A71.97718,71.97718,0,1,0,91.18359,157.84375a120.48811,120.48811,0,0,0-67.11865,54.14063,7.99981,7.99981,0,0,0,6.92432,12.00634l194.023.002a7.99957,7.99957,0,0,0,6.92431-12.00635Z"
        />
      </g>
    </g>
    <g v-else-if="displayWeight === 'light'">
      <line
        x1="176"
        y1="56"
        x2="224"
        y2="56"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="200"
        y1="32"
        x2="200"
        y2="80"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M30.989,215.99064a112.03731,112.03731,0,0,1,194.02311.002"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M188.05124,118.18275a63.96647,63.96647,0,1,1-45.27249-84.46794"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <line
        x1="176"
        y1="56"
        x2="224"
        y2="56"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="200"
        y1="32"
        x2="200"
        y2="80"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M30.989,215.99064a112.03731,112.03731,0,0,1,194.02311.002"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M188.05124,118.18275a63.96647,63.96647,0,1,1-45.27249-84.46794"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <line
        x1="176"
        y1="56"
        x2="224"
        y2="56"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="200"
        y1="32"
        x2="200"
        y2="80"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M30.989,215.99064a112.03731,112.03731,0,0,1,194.02311.002"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M188.05124,118.18275a63.96647,63.96647,0,1,1-45.27249-84.46794"
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
  name: "PhUserPlus",
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
