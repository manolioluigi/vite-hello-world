<script>
export default {
    name: "Jumbotron",
    data(){
        return{
            image: '../../img/58582c01f034562c582205ff.png'
        }
    }
}
</script>

<template>

    <img :src="image" alt="jumbo">
  
</template>

<style scoped>

    img{
        width: 500px;
    }

</style>