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
        d="M83.77207,61.31625a48.00774,48.00774,0,1,1,84.03029,45.521v0L80,224v-.01149h96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <path
        d="M83.77207,61.31625a48.00774,48.00774,0,1,1,84.03029,45.521v0L80,224v-.01149h96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="displayWeight === 'fill'">
      <path
        d="M184,223.98828a8.00008,8.00008,0,0,1-8,8H80.43555q-.21827.01245-.43653.01221a8.00346,8.00346,0,0,1-6.26757-12.9751l87.54687-116.82178a40.00778,40.00778,0,1,0-70.1377-37.771A8,8,0,1,1,76.4043,58.2002a56.00758,56.00758,0,1,1,98.02734,53.11523c-.07324.1084-.14844.21484-.22754.31934L96.001,215.98828H176A8.00039,8.00039,0,0,1,184,223.98828Z"
      />
    </g>
    <g v-else-if="displayWeight === 'light'">
      <path
        d="M83.77207,61.31625a48.00774,48.00774,0,1,1,84.03029,45.521v0L80,224v-.01149h96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <path
        d="M83.77207,61.31625a48.00774,48.00774,0,1,1,84.03029,45.521v0L80,224v-.01149h96"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <path
        d="M83.77207,61.31625a48.00774,48.00774,0,1,1,84.03029,45.521v0L80,224v-.01149h96"
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
  name: "PhNumberTwo",
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
