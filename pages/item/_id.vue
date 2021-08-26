<template>
  <div>
    <h1>item page</h1>
    <div>item id: {{ $route.params.id }}</div>
  </div>
</template>

<script>
export default {
  // 校验参数
  validate({ params }) {
    return /^\d+$/.test(params.id)
  },
}
</script>