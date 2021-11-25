<template>
  <div>
    <AppHeader />
    <h1>Here is a test page</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Optio ipsum, quidem hic necessitatibus, illum ratione expedita consequuntur sint magni voluptas cum quod vero obcaecati. Voluptatem soluta autem vitae aliquid modi!</p>
    <AppFooter />
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'About this app',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'best place for testing'
        }
      ]
    }
  }
}
</script>

<style>

</style>
