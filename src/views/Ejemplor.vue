<template>
    <div>
        <navbar class="n"> </navbar>
    <div class="conten">
        <siderbar> </siderbar>
    </div>
    <h1>
        ejemplo daniel
    </h1>

    
<div>
    <footervue class="ff"> </footervue>
</div>
       
       
        
       
       
    </div>
    

</template>
   <style>
   .ff{

    margin-top:600px ;

   }
   </style>
<script>
import navbar from '../components/navbar.vue'
import siderbar from '../components/siderbar.vue'
import footervue from '../components/footer.vue'


export default{
    name:"Ejemplor",
    props:{

    },

    data(){
        return{

        }
    },
    methods(){


    },
    computed:{

    },
    components:{
       navbar, siderbar,footervue
    },
    mounted (){

    },



}
</script>
