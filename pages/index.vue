<template>
  <div>
    <h1 class="">Lorem, ipsum dolor.</h1>

    <vs-row>
      <vs-col lg="4">
        <PokeCard :pokedata="pokedata" />
      </vs-col>
    </vs-row>
  </div>
</template>

<script>
import PokeCard from '../components/PokeCard'
export default {
  components: {
    PokeCard,
  },
  props: {
    pokedata: Object,
  },
  methods: {},
  created: {

  },
}
</script>

<style>
  
</style>
