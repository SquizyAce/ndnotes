<template>
  <div class="dialog" :style="model? '' : 'display: none'">
    <div class="dialog__header">{{ title }}</div>
    <div class="dialog__body">
      <slot/>
    </div>
  </div>
</template>
<script>
export default {
  props:{
    model:{
      type: Boolean
    },
    title: {
      type: String
    }
  }
}
</script>