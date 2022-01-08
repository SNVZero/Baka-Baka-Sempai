<template>
  <Reviews/>
  <Partners/>
  <Faq/>
  <Webform/>

</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
import Reviews from '@/components/Reviews.vue'
import Faq from '@/components/Faq.vue'
import Webform from '@/components/Webform.vue'
import Partners from '@/components/Partners.vue'
export default {
  name: 'App',
  components: {
    Reviews,
    Faq,
    Webform,
    Partners
  }
}
</script>

<style>

</style>
