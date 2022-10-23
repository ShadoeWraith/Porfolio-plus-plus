<template>
  <nav class="flex bg-transparent text-white py-4 border-b border-slate-2300">
    <h1 class="mr-auto ml-auto text-2xl">Portfolio++</h1>
    <ul class="flex text-md gap-4 items-center ml-auto mr-auto">
      <li class="nav-item"><a href="/">Home</a></li>
      <li class="nav-item"><a href="/network">Network</a></li>
      <li class="nav-item"><a href="/profile">Profile</a></li>
      <li class="nav-item"><a href="/logout">Logout</a></li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
@import url('../style.css');
@layer components {
  .nav-item {
    @apply hover:text-sky-400 cursor-pointer rounded-md px-1 duration-200;
  }
}
</style>
