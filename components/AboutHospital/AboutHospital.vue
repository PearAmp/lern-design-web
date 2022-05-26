<template>
<div class="container">
    <h2>HOSPITAL</h2>
    <v-combobox v-for="n in 4" :key="n"
      v-model="model"
      :items="items"
      :search-input.sync="search"
      hide-selected
    
      multiple
      persistent-hint
      small-chips
    >
      <template v-slot:no-data>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title>
              No results matching "<strong>{{ search }}</strong>". Press <kbd>enter</kbd> to create a new one
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </template>
    </v-combobox>
</div>
  
</template>

<script>
export default {
    name: 'AboutHospital',
    data: () => ({
      items: ['Liverpool', 'Lisburn', 'Manchester', 'Oxford'],
      model: ['England'],
      search: null,
    }),

    watch: {
      model (val) {
        if (val.length > 5) {
          this.$nextTick(() => this.model.pop())
        }
      },
    },

}
</script>

<style lang="scss" scoped>

</style>