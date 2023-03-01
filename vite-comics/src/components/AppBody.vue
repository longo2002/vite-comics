<template>
    <div class="container-body">
        <div class="hero-top">
            {{ msg }}
        </div>
        <div class="hero-bottom">
            <ul class="list-group">
                <li class="list-item">
                    <div>
                        <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                        <span>digital comics</span>
                    </div>
                </li>
                <li class="list-item">
                    <div>
                        <img src="../assets/buy-comics-merchandise.png" alt="merchandise">
                        <span>merchandise</span>
                    </div>
                </li>
                <li class="list-item">
                    <div>
                        <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
                        <span>subscriptions</span>
                    </div>
                </li>
                <li class="list-item">
                    <div>
                        <img src="../assets/buy-comics-shop-locator.png" alt="shop-locator">
                        <span>shop-locator</span>
                    </div>
                </li>
                <li class="list-item">
                    <div>
                        <img src="../assets/buy-dc-power-visa.svg" alt="dc-power-visa">
                        <span>dc-power-visa</span>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            msg: "--> Content here <--"
        }
    }
}
</script>
  
<style>
img {
    height: 100%;
}

.container-body {
    height: calc(100% - 280px);
}

.container-body div {
    height: 250px;
    display: flex;
    align-items: center;
}

.hero-top {
    font-size: 24px;
    font-weight: 900;
    background-color: #1c1c1c;
}

.hero-bottom {
    background-color: #0282f9;
    display: flex;
    align-items: center;
    justify-content: center;
}

.list-group {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    text-transform: uppercase;
    font-weight: 400;
    gap: 25px;
}

.list-group div {
    height: 70px;
    gap: 10px;
}
</style>