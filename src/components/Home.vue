<template>
    <div>
        <img v-bind:src="data.img">
        <p>{{ data.name }}</p>
    </div>
</template>

<script>
export default {

    data(){
        return{
            data:{
                img: '../asset/logo.png',
                name: 'LoGoVue'
            }
        }
    }
}
</script>


