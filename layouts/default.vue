<template>
  <v-app dark>
    
    
    <v-main>
      <HeaderBar />

        <Nuxt />
    </v-main>
    
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'News.',
    }
  },
}
</script>
