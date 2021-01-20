<template>
    <footer>
        <p>{{ footerText }}</p>
    </footer>
</template>

<script>
export default {
    name: 'footer',

    data(){
        return{
            footerText: 'Adnan Bacic'
        }
    }
}
</script>

<style scoped>
    footer{
        background-color: #121212;
        color: white;
        text-align: center;
        width: 100%;
        padding: 20px 0px 20px 0px;
    }
</style>