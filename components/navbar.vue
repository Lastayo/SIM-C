<template>
  <div>
    <nav class="bg-white-800 p-4">
      <div class="flex justify-end space-x-10 mt-6 mx-20">
        <ul class="flex space-x-10 text-lg font-semibold">
          <li>
            <a @click="scrollTo('#Beranda')" id="Beranda" class=" hover:text-blue-600">Beranda</a>
          </li>
          <li>
            <a @click="scrollTo('#Tujuan-kami')" class=" hover:text-blue-600">Tujuan Kami</a>
          </li>
          <li>
            <a @click="scrollTo('#Tutorial')" class=" hover:text-blue-600">Tutorial</a>
          </li>
          <li>
            <a @click="scrollTo('#Media-pembelajaran')" class=" hover:text-blue-600">Media Pembelajaran</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script setup>
const scrollTo = (target) => {
  const element = document.querySelector(target)
  if (element) {
    window.scrollTo({
      top: element.offsetTop,
      behavior: 'smooth'
    })
  }
}
</script>