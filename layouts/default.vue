<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <!--Page content-->
    <div class="container mx-auto p-4">
      <slot />
      <!--This is where the page content will be rendered-->
    </div>
  </div>
</template>

<script>
export default {
  name: "Default",
};
</script>

<style scoped>
.router-link-exact-active {
  color: bg-green-500;
}
</style>
