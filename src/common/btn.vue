<template>
  <div :class="[btnClass,cname]">

  </div>
</template>

<script>
export default {
  name: 'btn',
  props: {
    cname: {
      type: 'String',
      default: ''
    }
  },
  data () {
    return {
      btnClass: 'btn'
    }
  }
}
</script>

<style lang="scss">
@import ""
.btn {
  @include btn;
}
</style>
