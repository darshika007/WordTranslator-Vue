<style>
    @import '../Translateoutput/translateoutput.css';
</style>
<template>
  <h2 class="text-success">{{translateText}}</h2>
</template>

<script>

export default {
  name: 'translateOutput',
  props: ['translateText']
}

</script>

