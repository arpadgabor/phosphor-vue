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
        d="M180,48h.00006A27.99994,27.99994,0,0,1,208,75.99994V76a28,28,0,0,1-28,28H152a0,0,0,0,1,0,0V76a28,28,0,0,1,28-28Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M48,48H76a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,76.00006,104H76A28,28,0,0,1,48,76V48A0,0,0,0,1,48,48Z"
        transform="translate(152 152) rotate(180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M152,152h28a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,180.00006,208H180a28,28,0,0,1-28-28V152A0,0,0,0,1,152,152Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <path
        d="M76,152h.00006A27.99994,27.99994,0,0,1,104,179.99994V180a28,28,0,0,1-28,28H48a0,0,0,0,1,0,0V180A28,28,0,0,1,76,152Z"
        transform="translate(152 360) rotate(-180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <rect
        x="104"
        y="104"
        width="48"
        height="48"
        stroke-width="24"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M180,48h.00006A27.99994,27.99994,0,0,1,208,75.99994V76a28,28,0,0,1-28,28H152a0,0,0,0,1,0,0V76a28,28,0,0,1,28-28Z"
        opacity="0.2"
      />
      <path
        d="M48,48H76a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,76.00006,104H76A28,28,0,0,1,48,76V48A0,0,0,0,1,48,48Z"
        transform="translate(152 152) rotate(180)"
        opacity="0.2"
      />
      <path
        d="M152,152h28a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,180.00006,208H180a28,28,0,0,1-28-28V152A0,0,0,0,1,152,152Z"
        opacity="0.2"
      />
      <path
        d="M76,152h.00006A27.99994,27.99994,0,0,1,104,179.99994V180a28,28,0,0,1-28,28H48a0,0,0,0,1,0,0V180A28,28,0,0,1,76,152Z"
        transform="translate(152 360) rotate(-180)"
        opacity="0.2"
      />
      <path
        d="M76,152h.00006A27.99994,27.99994,0,0,1,104,179.99994V180a28,28,0,0,1-28,28H48a0,0,0,0,1,0,0V180A28,28,0,0,1,76,152Z"
        transform="translate(152 360) rotate(-180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M180,48h.00006A27.99994,27.99994,0,0,1,208,75.99994V76a28,28,0,0,1-28,28H152a0,0,0,0,1,0,0V76a28,28,0,0,1,28-28Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M48,48H76a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,76.00006,104H76A28,28,0,0,1,48,76V48A0,0,0,0,1,48,48Z"
        transform="translate(152 152) rotate(180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M152,152h28a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,180.00006,208H180a28,28,0,0,1-28-28V152A0,0,0,0,1,152,152Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <rect
        x="104"
        y="104"
        width="48"
        height="48"
        stroke-width="16"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M180,144H160V112h20a36,36,0,1,0-36-36V96H112V76a36,36,0,1,0-36,36H96v32H76a36,36,0,1,0,36,36V160h32v20a36,36,0,1,0,36-36ZM160,76a20,20,0,1,1,20,20H160ZM56,76a20,20,0,0,1,40,0V96H76A20.0226,20.0226,0,0,1,56,76ZM96,180a20,20,0,1,1-20-20H96Zm16-68h32v32H112Zm68,88a20.0226,20.0226,0,0,1-20-20V160h20a20,20,0,0,1,0,40Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M180,48h.00006A27.99994,27.99994,0,0,1,208,75.99994V76a28,28,0,0,1-28,28H152a0,0,0,0,1,0,0V76a28,28,0,0,1,28-28Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M48,48H76a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,76.00006,104H76A28,28,0,0,1,48,76V48A0,0,0,0,1,48,48Z"
        transform="translate(152 152) rotate(180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M152,152h28a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,180.00006,208H180a28,28,0,0,1-28-28V152A0,0,0,0,1,152,152Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <path
        d="M76,152h.00006A27.99994,27.99994,0,0,1,104,179.99994V180a28,28,0,0,1-28,28H48a0,0,0,0,1,0,0V180A28,28,0,0,1,76,152Z"
        transform="translate(152 360) rotate(-180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <rect
        x="104"
        y="104"
        width="48"
        height="48"
        stroke-width="12"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M180,48h.00006A27.99994,27.99994,0,0,1,208,75.99994V76a28,28,0,0,1-28,28H152a0,0,0,0,1,0,0V76a28,28,0,0,1,28-28Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M48,48H76a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,76.00006,104H76A28,28,0,0,1,48,76V48A0,0,0,0,1,48,48Z"
        transform="translate(152 152) rotate(180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M152,152h28a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,180.00006,208H180a28,28,0,0,1-28-28V152A0,0,0,0,1,152,152Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <path
        d="M76,152h.00006A27.99994,27.99994,0,0,1,104,179.99994V180a28,28,0,0,1-28,28H48a0,0,0,0,1,0,0V180A28,28,0,0,1,76,152Z"
        transform="translate(152 360) rotate(-180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <rect
        x="104"
        y="104"
        width="48"
        height="48"
        stroke-width="8"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M180,48h.00006A27.99994,27.99994,0,0,1,208,75.99994V76a28,28,0,0,1-28,28H152a0,0,0,0,1,0,0V76a28,28,0,0,1,28-28Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M48,48H76a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,76.00006,104H76A28,28,0,0,1,48,76V48A0,0,0,0,1,48,48Z"
        transform="translate(152 152) rotate(180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M152,152h28a28,28,0,0,1,28,28v.00006A27.99994,27.99994,0,0,1,180.00006,208H180a28,28,0,0,1-28-28V152A0,0,0,0,1,152,152Z"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <path
        d="M76,152h.00006A27.99994,27.99994,0,0,1,104,179.99994V180a28,28,0,0,1-28,28H48a0,0,0,0,1,0,0V180A28,28,0,0,1,76,152Z"
        transform="translate(152 360) rotate(-180)"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <rect
        x="104"
        y="104"
        width="48"
        height="48"
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
  name: "PhCommand",
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
