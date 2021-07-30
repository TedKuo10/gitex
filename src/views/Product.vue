<template>
  <div>
    <h2>單一產品頁面</h2>
    {{ id }}
  </div>
</template>

<script>
export default {
  data () {
    return {
      id: ''
    }
  },
  created () {
    const id = this.$route.params.id
    this.id = id
  }
}
</script>
