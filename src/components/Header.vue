<script setup>

const props = defineProps ({
 name:{
   type: String,
   required: true,
 },
 typeButton:{
   type: String,
   default: 'like',
 }
})
</script>
<template>
<header class="d-flex flex-wrap justify-content-right py-3 mb-4 border-bottom">
      <a href="/" class="d-flex align-items-right mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
        <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"></use></svg>
        <span class="fs-4"><h1>Cities of the World</h1></span>
      </a>

      <ul class="nav nav-pills">
        <li class="nav-item"><a href="#" class="nav-link active" aria-current="page">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link">-About</a></li>
        <li class="nav-item"><a href="#" class="nav-link">-Contact</a></li>
      </ul>
    </header>
</template>

