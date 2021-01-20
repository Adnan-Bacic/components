<template>
    <div id="content">
        <div class="contentBox">
            <h1>{{ msg }}</h1>
            <img src="http://placehold.it/300x300?text=Dummy%20Image">
        </div>

        <div class="contentBox">
            <h1>{{ msg }}</h1>
            <img src="http://placehold.it/300x300?text=Dummy%20Image">
        </div>
        
        <div class="contentBox">
            <h1>{{ msg }}</h1>
            <img src="http://placehold.it/300x300?text=Dummy%20Image">
        </div>
    </div>
</template>

<script>
export default {
    name: 'Content',

    data(){
        return{
            msg: 'Content'
        }
    }
}
</script>

<style scoped>
h1{
    text-align: center
}
    #content{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }
    .contentBox{
        
    }
</style>