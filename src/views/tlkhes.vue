<template>
    <div>
  
        <div class=" flex m-0 p-0  overflow-x-hidden bg-[#ECECF3]">

      

            <SidBar  class=" w-1/5"></SidBar>

          
        
        
        <div class=" w-4/5">
            
            <NavBarVisitore></NavBarVisitore>

            <div class=" text-ms text-start mx-10 text-[#503E9D] my-3" >
                الصفحة  الرئيسية &gt;  خدمات معين &gt; معين 
</div>

</div>
</div>
</div>
</template>

<script>

import NavBarVisitore from '../components/NavBarVisitore'
import SidBar from '../components/SidBar.vue'
export default {
    name:'TalkhesVue',
    components:{
        NavBarVisitore,
        SidBar,
    },}
    </script>