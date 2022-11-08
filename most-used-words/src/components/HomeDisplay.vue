<template>
  <v-container fluid>
    <div class="pills">
      <PillDisplayVue v-for="word in groupedWords" :key="word.name" :name="word.name" :amount="word.amount"/>
    </div>
  </v-container>
</template>

<script>
import PillDisplayVue from './PillDisplay.vue';

export default {
  comments: {PillDisplayVue},
  data: function(){
    return {
      groupedWords: [
        { name: 'you', amount: 900},
        {name: 'he', amount: 853},
        {name: 'i', amount: 1234} 
      ]
    }
  }
}
</script>

<style>

</style>