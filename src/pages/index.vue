<template>
  <q-page class="flex flex-center">
    <img class="gramado" src="https://cartolafc.globo.com/dist/3.5.7/img/campinho-sem-borda.svg">
  </q-page>
</template>

<style>
.gramado {
  width: 90%;
}
</style>

<script>
import draggable from 'vuedraggable'
export default {
  name: 'PageIndex',
  data () {
    return {
    }
  },
  components: {
    draggable
  }
}
</script>
