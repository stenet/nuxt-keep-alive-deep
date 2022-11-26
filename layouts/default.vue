<template>
  <div class="flex gap-4">
    <NuxtLink to="/page1">Page 1</NuxtLink>
    <NuxtLink to="/page2">Page 2</NuxtLink>
    <NuxtLink to="/page3">Page 3</NuxtLink>
    <NuxtLink to="/page4">Page 4</NuxtLink>
    <NuxtLink to="/page5">Page 5</NuxtLink>
    <NuxtLink to="/page6">Page 6</NuxtLink>
  </div>
  <div class="font-semibold text-lg py-6">
    <h2>Default</h2>
  </div>
  <div>
    <slot></slot>
  </div>
</template>
