<template>
</template>

<script>
module.exports = {
  props: ['href'],
  mounted() {
    location.href = this.href
  }
}
</script>
