<template>
  <div>
    <div class="container">
      <NuxtLayout name="error">
        <template #header>
          <h1>Khum coá gì ở đây hết</h1>
        </template>
        <template #redirectEl>
          <NuxtLink to="/">Go back to Home</NuxtLink>
        </template>

        
      </NuxtLayout>
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>
