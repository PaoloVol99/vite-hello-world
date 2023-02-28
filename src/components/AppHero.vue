<template>
    <div class="jumbo">
        <h1>{{ jumbotronTitle }}</h1>
        <h3>{{ jumbotronSubtitle }}</h3>
    </div>
</template>

<script>
export default {
    data() {
        return {
            jumbotronTitle: 'Questo è un jumbotron',
            jumbotronSubtitle: 'Se ho capito bene'
        }
    }
}

</script>

<style>

.jumbo {
    background-image: url('/jumbo-sfondo.webp');
    width: 900px;
    padding: 110px;
}

.jumbo h1,
.jumbo h3 {
    background-color: rgba(0, 0, 0, 0.5);
    line-height: 150px;
}

.jumbo h3 {
    line-height: 100px;
    font-size: 30px;
}

</style>