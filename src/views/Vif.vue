<template>
    <div>
        <siderbar> </siderbar>
        <div v-if="Math.random()>0.3">
        <p> holaaa </p>
        </div>
    </div>
</template>
<script>
import siderbar from '../components/siderbar.vue'

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
        siderbar
    },
    mounted (){

    },


}
</script>
