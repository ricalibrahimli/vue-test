<template>
    <div class="first-title">
         <h1 class="title">{{ title }}</h1>
         <p class="text1">{{ text1 }}</p>
         <p class="">just </p>
    </div>
   
</template>


<script>
export default {
    data(){
        return{
           title: 'i am component',
           text1: ' lorem ipsum'
        }
    }
}
</script>

<style scoped>
.first-title{
    display: flex;
    justify-content: center;
}
.title{
    display: flex;
    justify-content: center;
}
.text1{
    display: flex;
    justify-content: center;
}
</style>