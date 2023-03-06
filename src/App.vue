<script setup>

</script>

<template>
  <VForm>
    <VField
      label="電子信箱"
      name="email"
      type="email"
      rules="required|email"
    />
    <ErrorMessage name="email"/>
  </VForm>
</template>

<style scoped>

</style>