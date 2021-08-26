<template>
  <div>
    <p>首页</p>
    <img src="~/assets/images/crayon.jpeg" alt="crayon">
    <div>
      <button @click="onToast">toast</button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    onToast() {
      this.$toast.success('Successfully authenticated')
    }
  }
}
</script>