<template>
  <div>
    <Nuxt />
    <AppHeader />
    <footer :pageInfo="siteInfo"> {{ siteInfo.pageName }} {{ siteInfo.author }}</footer>
  </div>
</template>

<script>
export default {
  data () {
    return {
      siteInfo: {
        pageName: 'Card Test',
        author: 'Devon',
        dateStarted: '22/11/2021'
      },
      vueReview: {
        annoying: 'Kind of',
        lost: 'yep',
        helpful: 'A lot to learn but seems handy'
      }
    }
  }
}
</script>

<style>

</style>
