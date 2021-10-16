<template>
<div class="container mx-auto flex flex-col items-center bg-gray-100 p-4">
  <div class="container">
    <div class="w-full my-4"></div>
    <section>
        <input-field />
    </section>

      
      
     

  </div>
</div>
</template>

<script>

import InputField from './components/InputField.vue'


export default {
  name: 'App',
  components: {
      InputField,
  },

}
</script>


<style src="./app.css">

</style>
