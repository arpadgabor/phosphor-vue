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
      <rect
        x="-10"
        y="98"
        width="176"
        height="60"
        rx="8"
        transform="translate(206 50) rotate(90)"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="90"
        y="98"
        width="176"
        height="60"
        rx="8"
        transform="translate(306 -50) rotate(90)"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <rect
        x="-8"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(208 48) rotate(90)"
        opacity="0.2"
      />
      <rect
        x="88"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(304 -48) rotate(90)"
        opacity="0.2"
      />
      <rect
        x="-8"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(208 48) rotate(90)"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="88"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(304 -48) rotate(90)"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <g>
        <rect x="40" y="32" width="80" height="192" rx="16" />
        <rect x="136" y="32" width="80" height="192" rx="16" />
      </g>
    </g>
    <g v-else-if="displayWeight === 'light'">
      <rect
        x="-8"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(208 48) rotate(90)"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="88"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(304 -48) rotate(90)"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <rect
        x="-8"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(208 48) rotate(90)"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="88"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(304 -48) rotate(90)"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <rect
        x="-8"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(208 48) rotate(90)"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
      <rect
        x="88"
        y="96"
        width="176"
        height="64"
        rx="8"
        transform="translate(304 -48) rotate(90)"
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
  name: "PhColumns",
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
