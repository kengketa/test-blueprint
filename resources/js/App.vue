<template>
    <div class="bg-red-500 min-h-screen flex justify-center items-center text-xl text-white">
        {{data}}
    </div>
</template>
<script>
export default {
    props:{
        data:{
            type:String,
            default:null
        }
    },
    data() {
        return {
            message: 'Hello World!',
        }
    }
}
</script>
