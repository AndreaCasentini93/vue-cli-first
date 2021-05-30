<template>
      <h1 id="title">La mia prima app con Vue CLI!</h1>
</template>

<script>
export default {
    name: 'Title'
}
</script>

<style scoped>
    #title {
        padding-top: 20px;
        text-align: center;
        text-shadow: 5px 5px 0px #000000;
        font-size: 50px;
        font-weight: 800;
        color: #AAD945;
    }

    @media screen and (max-width: 768px) {
        #title {
            font-size: 40px;
        }
    }
</style>