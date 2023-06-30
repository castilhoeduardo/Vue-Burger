<template>
    <div id="main-banner">
        <h1>Make Your Burguer</h1>
    </div>
</template>

<script>
export default {
    name:"Banner"

}
</script>

<style scoped>

    #main-banner {
        background-image: url('/public/img/burger.jpg');
        background-position: 0 -250px;
        background-size: cover;
        height: 600px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #b3842d; 
        background-color: #222;
        font-size: center;
        font-size: 60px;
       
        padding: 20px 40px;
        }
</style>