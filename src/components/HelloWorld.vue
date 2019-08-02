<template>
  <div id="app">
    <formio ref="formio" src="http://192.168.2.222:3001/user/register"></formio>
  </div>
</template>

<script>
  import { Form } from 'vue-formio';
  export default {
      name: 'app',
      components: { formio: Form },
      data(){
        return{

        }
      },
      mounted(){
        console.log(this.$refs.formio);
      }
  }
</script>

<style>

</style>
