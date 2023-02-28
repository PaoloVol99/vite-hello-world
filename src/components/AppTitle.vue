<template>
    <div>
        <h1 class="bg-orange">{{ title }}</h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'La mia prima app con Vite!'
        }
    }
}

</script>

<style>

.bg-orange {
    color: white;
    background-color: orange;
    padding: 20px;
    border-radius: 10px;
}

</style>