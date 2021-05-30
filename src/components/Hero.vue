<template>
    <div id="jumbotron">
        <Title/>
    </div>
</template>

<script>
import Title from './Title';

export default {
    name: 'Hero',
    components: {
        Title
    }
}
</script>

<style scoped>
    #jumbotron {
        width: 100%;
        height: 100vh;
        background-image: url('https://ahrefs.com/blog/it/wp-content/uploads/2020/07/fb-javascript-seo_it.png');
        background-position: center;
        background-size: cover;
    }
</style>