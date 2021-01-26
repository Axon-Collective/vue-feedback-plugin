<template>
  <div id="app">
    <OpenFormButton/>
    <VueFeedbackPopup/>
  </div>
</template>

<script>
import OpenFormButton from './components/OpenFormButton.vue'
import VueFeedbackPopup from './components/VueFeedbackPopup.vue'


export default {
  name: 'app',
  components: {
    OpenFormButton,
    VueFeedbackPopup
  }
}
</script>

<style>

</style>
