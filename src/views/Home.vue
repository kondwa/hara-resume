<template>
  <div class="home">
    <!--img alt="Vue logo" src="../assets/logo.png"-->
    <Resume msg="Kondwani Hara's Resume"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Resume from '@/components/Resume.vue'

export default {
  name: 'Home',
  components: {
    Resume
  }
}
</script>
