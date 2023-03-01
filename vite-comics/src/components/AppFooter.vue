<template>
    <div class="container-footer">
        {{ msg }}
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            msg: "Questo è il footer"
        }
    }
}
</script>
  
<style>
.container-footer {
    background-color: #02f969;
    height: 125px;
}
</style>
