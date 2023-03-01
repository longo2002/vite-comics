<template>
    <div class="bg-white">
        {{ msg }}
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            msg: "Questo è l' header"
        }
    }
}
</script>
  
<style>
.bg-white {
    background-color: #ffffff;
    color: #0282f9;
}
</style>
  