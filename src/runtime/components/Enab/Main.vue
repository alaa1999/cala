<template>
  <!-- Application -->
  <div p="4">
    <UiInput label="Username" />
    <UiButton color="success">
Add Section
</UiButton>
<UiButton color="error" >Cancel </UiButton>


   <div class="bg-amber-500 h-10">
     hiii
   </div> 
   
   </div> 

 
 
</template>

<script setup>
  import { ref, computed } from '#imports'
  new Vue({
  el: '#tags',
  data: {
    tags: ['JavaScript', 'MVVM', 'Vue.js']
  }
})
// const props = defineProps({
//   app: {
//     type: Object,
//     required: true,
//   },

// });

</script>
