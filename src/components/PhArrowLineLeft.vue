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
        x1="232.00373"
        y1="128"
        x2="80.00373"
        y2="128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <polyline
        points="152.004 56 80.004 128 152.004 200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="40.00373"
        y1="48"
        x2="40.00373"
        y2="208"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="displayWeight === 'duotone'">
      <line
        x1="232.00373"
        y1="128"
        x2="72.00373"
        y2="128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <polyline
        points="144.004 56 72.004 128 144.004 200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="40.00373"
        y1="48"
        x2="40.00373"
        y2="208"
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
          d="M232.00391,120H91.31738l58.34278-58.34326a7.99984,7.99984,0,1,0-11.31348-11.31348L66.34961,122.34058q-.28125.28125-.53369.59008c-.07129.087-.1333.179-.20069.26831-.08984.11927-.18212.23633-.26513.3606-.07373.11047-.1377.2251-.20557.33838-.06592.11035-.13525.21838-.19629.332-.0625.11682-.11523.23682-.17138.356-.05567.11767-.11426.2334-.16456.35425-.04736.11523-.08593.23291-.12793.34985-.04638.129-.0957.25659-.13574.38867-.03564.11792-.06152.23755-.09179.35657-.0337.13367-.07129.26575-.09815.402-.02734.13769-.04346.27685-.06348.41552-.01709.11963-.03955.23731-.05175.35852q-.03736.38234-.03858.76648l-.001.02222.001.02222q.00074.38379.03858.76648c.0122.12121.03466.23889.05175.35852.02.13867.03614.27783.06348.41552.02686.13623.06445.26831.09815.402.03027.119.05615.23865.09179.35657.04.13208.08936.25964.13574.38867.042.11694.08057.23462.12793.34985.0503.12085.10889.23658.16456.35425.05615.11914.10888.23914.17138.356.061.11365.13037.22168.19629.332.06787.11328.13184.22791.20557.33838.083.12427.17529.24133.26513.3606.06739.08935.1294.18127.20069.26831q.25267.308.53369.59008l71.99707,71.99732a7.99984,7.99984,0,1,0,11.31348-11.31348L91.31738,136H232.00391a8,8,0,1,0,0-16Z"
        />
        <path
          d="M40.00391,40a7.99977,7.99977,0,0,0-8,8V208a8,8,0,0,0,16,0V48A8.00009,8.00009,0,0,0,40.00391,40Z"
        />
      </g>
    </g>
    <g v-else-if="displayWeight === 'light'">
      <line
        x1="232.00373"
        y1="128"
        x2="72.00373"
        y2="128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <polyline
        points="144.004 56 72.004 128 144.004 200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="40.00373"
        y1="48"
        x2="40.00373"
        y2="208"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="displayWeight === 'thin'">
      <line
        x1="232.00373"
        y1="128"
        x2="72.00373"
        y2="128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <polyline
        points="144.004 56 72.004 128 144.004 200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="40.00373"
        y1="48"
        x2="40.00373"
        y2="208"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="displayWeight === 'regular'">
      <line
        x1="232.00373"
        y1="128"
        x2="72.00373"
        y2="128"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <polyline
        points="144.004 56 72.004 128 144.004 200"
        fill="none"
        :stroke="displayColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="40.00373"
        y1="48"
        x2="40.00373"
        y2="208"
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
  name: "PhArrowLineLeft",
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
