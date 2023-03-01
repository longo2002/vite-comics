<template>
    <div class="container-body">
        <div>
            {{ msg }}
        </div>
        <div>
            <ul class="list-group">
                <li class="list-item">
                    <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                    <span>digital comics</span>
                </li>
                <li class="list-item">
                    <img src="../assets/buy-comics-merchandise.png" alt="merchandise">
                    <span>digital comics</span>
                </li>
                <li class="list-item">
                    <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
                    <span>digital comics</span>
                </li>
                <li class="list-item">
                    <img src="../assets/buy-comics-shop-locator.png" alt="shop-locator">
                    <span>digital comics</span>
                </li>
                <li class="list-item">
                    <img src="../assets/buy-dc-power-visa.png" alt="dc-power-visa">
                    <span>digital comics</span>
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
.container-body div:first-child,
.container-body div:last-child {
    height: 125px;
    display: flex;
    align-items: center;
}

.container-body div:first-child {
    font-size: 24px;
    font-weight: 900;
    background-color: #1c1c1c;
}

.container-body div:last-child {
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
    gap: 25px;
}

.list-item img {
    width: 60px;
}

.list-item span {
    text-transform: uppercase;
}
</style>