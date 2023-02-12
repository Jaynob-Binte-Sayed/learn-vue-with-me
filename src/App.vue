<template>
  <div>
    <form-helper>
      <h2 slot="title">I am the slot title</h2>
      <p slot="text">I am the paragraph text for slot</p>
    </form-helper>
  </div>


</template>



<script>
import formHelper from './components/formHelper.vue';

export default {
  components:{
    'form-helper': formHelper
    
  },

  data () {
    return {
      title: 'I am a dynamic slot title'
        
    
    }
  },
  methods:{
    
  }

  
}
</script>

<style >

</style>
