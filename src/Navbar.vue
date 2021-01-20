<template>
    <div id="navbar">
        <h1>{{ msg }}</h1>
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Contact</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
    data(){
        return{
            msg: 'Navbar',
        }
    }
}
</script>

<style scoped>
    #navbar{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }
    ul{
        list-style-type: none;
        display: flex;
        flex-wrap: wrap;
        justify-content: flex-end;
        width: 100%;
    }
    li{
        margin: 0px 20px 0px 20px;
    }
</style>