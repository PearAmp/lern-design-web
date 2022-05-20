<template>
<v-app>
    <HeaderBar />
    <Contentbreaknews />
    <ContentLocalNews />
</v-app>
  
</template>

<script>
import HeaderBar from '/components/HeaderBar/HeaderBar.vue'
export default {
    components: { HeaderBar },
    name: 'layoutlocal',

}
</script>

