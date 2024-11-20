<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
            Fugit asperiores aliquam distinctio doloribus ad molestiae, 
            cupiditate architecto aperiam aliquid nobis!</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    
    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>