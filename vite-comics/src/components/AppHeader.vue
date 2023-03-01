<template>
    <div class="container-header">
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
        }
    },
    methods: {
    }
}
</script>
  
<style>
.container-header div {
    height: 125px;
    padding: 15px 30px;
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

.nav-bar li:hover {
    color: #0282f9;
}
</style>
  