

<template>
    <div class="container">
        <div class="jumbotron">
            <span class="text">Sono un paesaggio</span>
        </div>
    </div>
</template>

<script>
export default {
  name: 'MainJumbotron',
}
</script>

<style scoped>
.container{
    display: flex;
    justify-content: center;
}
.jumbotron{
    height: 200px;
    width: 400px;
    background-image: url(https://picsum.photos/seed/picsum/400/200);
    background-repeat: no-repeat;
    position: relative;
}
.text{
    color: white;
    font-size: 1.5rem;
    position: absolute;
    top: 10px;
    left: 10px;
}
</style>