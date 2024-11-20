<template>
    <div>
        <h2>About</h2>
        <h3>{{ data.message }}</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
            Fugit asperiores aliquam distinctio doloribus ad molestiae, 
            cupiditate architecto aperiam aliquid nobis!</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
            Fugit asperiores aliquam distinctio doloribus ad molestiae, 
            cupiditate architecto aperiam aliquid nobis!</p>
    </div>
</template>

<script setup>
/* GET Request */
//  const { data } = await useFetch('/api/ninja?name=naruto') 
/* POST Request */
const { data } = await useFetch('/api/ninja?name=naruto', {
    method: 'post',
    body: {
        age: 30
    }
})
</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px; 
    }
    p {
        margin: 20px 0;
    }
</style>