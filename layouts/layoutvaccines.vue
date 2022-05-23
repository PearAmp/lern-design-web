<template>
<v-app>
    <HeaderBar />
    <Contentvaccines />
    <Contentworldnews />
    <Contentnational />
    <Contentvedio />
    <ContentMost />
</v-app>
  
</template>

<script>
import HeaderBar from '/components/HeaderBar/HeaderBar.vue'
export default {
    components: { HeaderBar },
    name: 'layoutvaccines',

}
</script>

