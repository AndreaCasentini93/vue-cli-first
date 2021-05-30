<template>
    <div id="jumbotron">
        <Title/>
        <div class="wrapper">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/1200px-Node.js_logo.svg.png" alt="Node Js">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png" alt="Vue">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Npm-logo.svg/1200px-Npm-logo.svg.png" alt="Npm">
        </div>
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
        background-color: #02428A;
        background-image: url('https://ahrefs.com/blog/it/wp-content/uploads/2020/07/fb-javascript-seo_it.png');
        background-position: center;
        background-size: contain;
        background-repeat: no-repeat;
    }

    #jumbotron .wrapper {
        display: flex;
        justify-content: center;
        width: 100%;
    }

    #jumbotron img {
        height: 60px;
        margin: 20px 30px;
    }

    @media screen and (max-width: 768px) {
        #jumbotron .wrapper {
            display: flex;
            justify-content: center;
            width: 100%;
        }

        #jumbotron img {
            height: 30px;
            margin: 10px 20px;
        }
    }
</style>