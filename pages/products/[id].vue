<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore eligendi
            asperiores minus at non eum doloribus culpa, labore, a, rem placeat magnam
            fugiat voluptate facilis. Cupiditate quasi illum facere! Sapiente!
        </p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    
    definePageMeta({
        layout: "products",
    });
</script>

<style scoped></style>
