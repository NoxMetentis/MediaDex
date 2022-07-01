<template>
    <div class="fixed top-0 left-0 bg-gray-100 opacity-70 w-screen h-screen" @click.self="closeModal">
         <div class=" w-2/5 p-8 my-20 bg-gray-200 rounded-xl b-4 mx-auto text-center shadow-sm" :class="{sale:theme === 'sale'}">
           <slot>  
           </slot>
           <div class="stuff p-4 rounded-xl flex justify-between">
            <slot name="links" >
            </slot>
           </div>
         </div>
    </div>
</template>
<script>
export default {
    props: ['theme'],
    methods:{
        closeModal(){
            this.$emit('close')
        }
    }

}
</script>