<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header>
        <div class="logo">
            <!-- percorso assoluto perchè l'immagine è in public -->
            <img src="/Breaking_Bad_logo.svg.png" alt="logo breaking bad">
            <h1>Breaking Bad Api</h1>
        </div>
    </header>
</template>



<style lang="scss" scoped>

    header {
        img {
            width: 150px;
        }
        .logo {
            text-align: center;
            margin-top: 50px;
        }
    }
    h1 {
        font-size: 3rem;
        margin-top: 20px;
    }
</style>