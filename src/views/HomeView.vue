<template>
  <div class="home">
    <DispleyCal></DispleyCal>
        <ButtonNumber></ButtonNumber>
  </div>
</template>

<script>
// importar css bootstrap
import 'bootstrap/dist/css/bootstrap.css'
// @ is an alias to /src
import DispleyCal from '@/components/DispleyCal.vue'
import ButtonNumber from '@/components/ButtonNumber.vue'
export default {
  name: 'HomeView',
  components: {
    ButtonNumber,
    DispleyCal,
  }
}
</script>
