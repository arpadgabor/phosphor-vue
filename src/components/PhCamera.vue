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
        d="M208,208H48a16,16,0,0,1-16-16V80A16,16,0,0,1,48,64H79.99414l16-24h64l16,24H208a16,16,0,0,1,16,16V192A16,16,0,0,1,208,208Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <circle
        cx="128"
        cy="132"
        r="36"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M208,64H175.99414l-16-24h-64l-16,24H48A16,16,0,0,0,32,80V192a16,16,0,0,0,16,16H208a16,16,0,0,0,16-16V80A16,16,0,0,0,208,64ZM128,168a36,36,0,1,1,36-36A36,36,0,0,1,128,168Z"
        opacity="0.2"
      />
      <path
        d="M208,208H48a16,16,0,0,1-16-16V80A16,16,0,0,1,48,64H79.99414l16-24h64l16,24H208a16,16,0,0,1,16,16V192A16,16,0,0,1,208,208Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle
        cx="128"
        cy="132"
        r="36"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M208,56H180.27539l-13.625-20.4375A7.99942,7.99942,0,0,0,159.99414,32h-64a7.99943,7.99943,0,0,0-6.65625,3.5625L75.71289,56H48A24.0275,24.0275,0,0,0,24,80V192a24.0275,24.0275,0,0,0,24,24H208a24.0275,24.0275,0,0,0,24-24V80A24.0275,24.0275,0,0,0,208,56Zm-44,76a36,36,0,1,1-36-36A36.04043,36.04043,0,0,1,164,132Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M208,208H48a16,16,0,0,1-16-16V80A16,16,0,0,1,48,64H79.99414l16-24h64l16,24H208a16,16,0,0,1,16,16V192A16,16,0,0,1,208,208Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <circle
        cx="128"
        cy="132"
        r="36"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M208,208H48a16,16,0,0,1-16-16V80A16,16,0,0,1,48,64H79.99414l16-24h64l16,24H208a16,16,0,0,1,16,16V192A16,16,0,0,1,208,208Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <circle
        cx="128"
        cy="132"
        r="36"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M208,208H48a16,16,0,0,1-16-16V80A16,16,0,0,1,48,64H79.99414l16-24h64l16,24H208a16,16,0,0,1,16,16V192A16,16,0,0,1,208,208Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <circle
        cx="128"
        cy="132"
        r="36"
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
  name: "PhCamera",
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
