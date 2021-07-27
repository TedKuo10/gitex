<template>
  <div class="about">
    <h1>This is an about page {{ message }}</h1>
    <Card></Card>
  </div>
</template>

<script>
import Card from '@/components/Card.vue'

export default {
  data () {
    return {
      message: 'for vue'
    }
  },
  components: {
    Card
  }
}
</script>
