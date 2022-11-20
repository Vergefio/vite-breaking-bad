<script>
export default {
    name: 'AppMain'
}
</script>

<template>
  <main class="container">
    <div>
        <select name="select" id=""></select>
    </div>
    <div>
        <p>Found 62 characters</p>
    </div>
  </main>
</template>



<style lang="scss" scoped>
    main {
        min-height: 700px;
        padding: 50px 0;
        background-image: url('../assets/img/sfondo.jpg');
        background-size: cover;
    }
    select {
        width: 120px;
        height: 30px;
        margin-left: 15px;
    }
    p {
        padding: 15px 15px;
        margin: 40px 40px;
        height: 50px;
        background-color: #252525;
        font-weight: bold;
    }
</style>