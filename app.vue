<template>
  <header class="mt-auto flex flex-grow py-4 px-4 bg-teal-500">
    <div class="flex-grow">
      <a href="#" target="_blank"><img src="#"/></a>
    </div>
    <nav>
      <ul class="flex">
        <li class="pl-3"><a href="#">test</a></li>
        <li class="pl-3"><a href="#">test</a></li>
        <li class="pl-3"><a href="#">test</a></li>
      </ul>
    </nav>
  </header>
  <div class="w-full flex flex-col sm:flex-row flex-wrap sm:flex-nowrap py-4 flex-grow">
    <!-- fixed-width -->
    <div class="w-fixed w-full flex-shrink flex-grow-0 px-4">
        <div class="sticky top-0 p-4 w-full h-full">
          <img src="#"/>
        </div>
    </div>
    <nav class="w-fixed w-full flex-shrink flex-grow-0 px-2">
        
    </nav>
  </div>
  <footer class="bg-black mt-auto">
      ...
  </footer>
</template>

<script>

export default {
  components: {},
  data() {
    return {}
  },
}
</script>