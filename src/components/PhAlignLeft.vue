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
        x1="39.99414"
        y1="39.99512"
        x2="39.99414"
        y2="215.99512"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <rect
        x="80"
        y="56"
        width="104"
        height="52"
        rx="8"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="80"
        y="148"
        width="144"
        height="52"
        rx="8"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <rect x="72" y="56" width="112" height="56" rx="8" opacity="0.2" />
      <rect x="72" y="144" width="152" height="56" rx="8" opacity="0.2" />
      <rect
        x="72"
        y="144"
        width="152"
        height="56"
        rx="8"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <line
        x1="39.99414"
        y1="39.99512"
        x2="39.99414"
        y2="215.99512"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <rect
        x="72"
        y="56"
        width="112"
        height="56"
        rx="8"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M47.99414,39.99512v176a8,8,0,0,1-16,0v-176a8,8,0,0,1,16,0ZM80,120h96a16.01833,16.01833,0,0,0,16-16V64a16.01833,16.01833,0,0,0-16-16H80A16.01833,16.01833,0,0,0,64,64v40A16.01833,16.01833,0,0,0,80,120Zm136,16H80a16.01833,16.01833,0,0,0-16,16v40a16.01833,16.01833,0,0,0,16,16H216a16.01833,16.01833,0,0,0,16-16V152A16.01833,16.01833,0,0,0,216,136Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <line
        x1="39.99414"
        y1="39.99512"
        x2="39.99414"
        y2="215.99512"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <rect
        x="72"
        y="56"
        width="112"
        height="56"
        rx="8"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="72"
        y="144"
        width="152"
        height="56"
        rx="8"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <line
        x1="39.99414"
        y1="39.99512"
        x2="39.99414"
        y2="215.99512"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <rect
        x="72"
        y="56"
        width="112"
        height="56"
        rx="8"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="72"
        y="144"
        width="152"
        height="56"
        rx="8"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <line
        x1="39.99414"
        y1="39.99512"
        x2="39.99414"
        y2="215.99512"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <rect
        x="72"
        y="56"
        width="112"
        height="56"
        rx="8"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="72"
        y="144"
        width="152"
        height="56"
        rx="8"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
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
  name: "PhAlignLeft",
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
