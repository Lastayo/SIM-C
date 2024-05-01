<template>
  <div>
    <Navbar />
    <div class="container mx-auto p-4">
      <div class="flex justify-center gap-24 mt-20">
        <div class="my-32">
          <h1 class="text-6xl font-bold mb-4">
            <span style="color: blue">Launch</span>
            Your Web <br class="block" />
            Grow Your <span style="color: blue">Business</span>
          </h1>

          <p class="font-roboto text-[21px]">"Ready to stand out in the digital world? Get started by creating a <br>
            website at MBAHP! Find the diverse skilled talent and technical <br>
            support you need to create a stunning and effective website. Join <br>
            now and start building your amazing online presence with MBAHP!</p>
        </div>
        <div>
          <img src="/public/Banner1.svg" class="mt-4 h-[450px]">
        </div>
      </div>

      <div class="">
        <button class="border-2 border-blue-600 rounded-lg py-2 px-4 hover:bg-blue-600 hover:text-white"> Write to us </button>
      </div>

    </div>

  </div>
  <tentang/>
</template>

<script>
import Navbar from '@/components/Navbar'
import Visi from '@/components/visi'
import tentang from './components/tentang'

export default {
  components: {
    Navbar,
    Visi,
    tentang
  }
}
</script>
