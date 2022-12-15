<template>
    <header id="header">

        <div id="header-center">
          <img id="img-vue" src="../assets/images/vue.png" />
          <h1>MyNetWork</h1>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>

#header {
    width: 100%;
    height: 10vh;
    background-color: var(--secondary-bg-color);
    display: flex;
    flex-direction: row;
}

#header-center {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    padding-right: 10px;
}

#img-vue {
    width: 50px;
    height: 50px;
    margin-right: 10px;
}

</style>