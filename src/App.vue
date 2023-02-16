<template>
  <div>
    <show-Blogs></show-Blogs>
   

    
  </div>


</template>



<script>
import addBlog from './components/addBlog.vue';
import showBlogs from './components/showBlogs.vue';


export default {
  components:{
    'add-Blog': addBlog,
    'show-Blogs': showBlogs
  },
  

  data () {
    return {
    
        
    
    }
  },
  methods:{
    
  }

  
}
</script>

<style >

body{
  margin: 0;
  font-family: 'Nunito SemiBold';
}

</style>
