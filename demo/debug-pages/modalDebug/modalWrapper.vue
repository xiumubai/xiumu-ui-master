<template>
  <modal :show="value" />
</template>

<script>
import modal from './modal.vue'

export default {
  components: {
    modal
  },
  props: {
    value: {
      type: Boolean,
      default: false
    }
  }
}
</script>
