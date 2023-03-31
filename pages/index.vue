<template>
  <body>
    <TopNav />
  </body>
</template>


<script>
import TopNav from '../components/nav/TopNav.vue'
import bigImage from '../components/gallery/bigImage.vue'

export default {

  name: 'IndexPage',
  components: {
    TopNav,
    bigImage
  }
}

</script>