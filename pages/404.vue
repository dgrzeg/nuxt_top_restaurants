<template>
  <div>
    <div class="container">
      <NuxtLayout name="error">
        <template #header>
          <h1>Page not found!</h1>
        </template>

        <template #redirect>
          <button
            class="btn btn-primary btn-large"
            @click="$router.push('/restaurants')"
          >
            Go Back
          </button>
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
.sadface {
  margin: 2rem;
  width: 10rem;
}
</style>
