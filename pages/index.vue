<template>
  <h1>Welcome to my first nuxt app</h1>
</template>

<script>
export default {
  name: 'IndexPage',
  head () {
    return {
      title: 'Application Nuxt Post | Home',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Website about posts'
        }
      ],
      htmlAttrs: {
        lang: 'en'
      }
    }
  }
}
</script>
