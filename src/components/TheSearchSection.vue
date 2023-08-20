<script>
</script>
<template>
    <div class="container">
        <img src="src/assets/TechStalk Logo.png" alt="">
        <form action="">
            <input id="search_bar" type="text" placeholder="Search for someone">
        </form>
    </div>
</template>
<style scoped>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 40px
}

#search_bar {
    background-color: #303030;
    width: 45vw;
    height: 30px;
    border-radius: 20px;
    color: whitesmoke;
    padding-left: 20px;
}
</style>