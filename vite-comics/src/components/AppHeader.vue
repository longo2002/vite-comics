<template>
    <div class="container">
        <div>
            <img src="../assets/dc-logo.png" alt="">
            <ul class="nav-bar">
                <li>characters</li>
                <li>comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>
            </ul>
        </div>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            msg: "Questo è l' header"
        }
    },
    methods: {
        helloFunction() {
            console.log('Ciao!')
        }
    }
}
</script>
  
<style>
.container div {
    width: 1250px;
    padding: 10px;
    background-color: #ffffff;
    color: black;
    display: flex;
    justify-content: space-between;
}

.nav-bar {
    list-style: none;
    display: flex;
    align-items: center;
    gap: 15px;
    text-transform: uppercase;
    font-weight: 750;
}
</style>
  