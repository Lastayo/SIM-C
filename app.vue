<template>
  <div class="bg-gray-100 bg-full">
    <Navbar />
    <tentang />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import Footer from '@/components/footer'
import tentang from './components/tentang'

export default {
  components: {
    Navbar,
    Footer,
    tentang
  }
}
</script>
