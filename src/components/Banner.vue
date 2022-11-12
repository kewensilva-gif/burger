<template>
    <div id="main-burger">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner',
}

</script>


<style scoped>
    #main-burger {
        background-image: url('../../src/assets/burger.jpg');
        background-repeat: no-repeat;
        background-position: 0 50%;
        background-size: cover;
        height: 85vh;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-burger h1 {
        color: var(--bg-branco);
        text-align: center;
        font-size: 60px;
        background-color: var(--bg-cinza-principal);
        padding: 20px 40px;
    }
</style>