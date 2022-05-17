<template>
  <div>
    <slot name="header" />
    <div>
      <img
        src="https://i.pinimg.com/564x/24/8c/c4/248cc4eec11b158d6eaf49c7088022a4.jpg"
        alt="sadface"
        class="sadface"
      />
    </div>
    <slot name="redirect" />
  </div>
</template>

<style scoped>
.sadface {
  margin: 2rem;
  width: 10rem;
}
</style>
