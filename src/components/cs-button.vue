<template>
  <button class="cs-button">
    <csIcon v-if="icon" :iconName="icon" />
    <span><slot/></span>
  </button>
</template>
<script>
import csIcon from './icons.vue';
export default {
  components: {
    csIcon
  },
  props:{
    disabled: {
      type: Boolean,
      default: false
    },
    type: {
      type: String,
      default: ''
    },
    icon: {
      type: String,
      default: undefined
    }
  }
}
</script>