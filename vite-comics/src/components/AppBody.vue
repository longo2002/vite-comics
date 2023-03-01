<template>
    <div class="bg-black">
        {{ msg }}
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            msg: "Questo è il body"
        }
    },
}
</script>
  
<style>
.bg-black {
    background-color: #1c1c1c;
}
</style>