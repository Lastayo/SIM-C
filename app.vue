<template>
  <div>
    <Navbar />
    

  </div>
  <tentang />
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
