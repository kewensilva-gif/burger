<template>
    <footer id="footer">
        <p>Make Your Burger &copy; 2022</p>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    #footer {
        height: 200px;
        background: var(--bg-cinza-principal);
        border-top: 4px solid var(--bg-cinza-secundario);
        color: var(--bg-amarelo-principal);
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }
</style>