<template>
    <div class="fixed top-0 left-0 bg-gray-100 w-screen h-screen bg-opacity-50 z-50" @click.self="closeModal">
         <div class=" w-3/5 p-8 my-20 bg-gray-200  rounded-xl mx-auto text-center shadow-sm">
           <slot>  
           </slot>
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