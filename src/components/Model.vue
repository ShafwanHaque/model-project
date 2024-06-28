<template>
    <div class="backdrop">
        <div class="model">
            <h1>Skidoo</h1>
            <p>Model Content</p>
        </div>
    </div>
</template>
<!-- use scoped for only apply css in this page components -->
<style scoped>
.model{
    width: 400px;
    padding: 20px;
    margin: 100px auto;
    background: white;
    border-radius: 10px;
}
.backdrop{
    top: 0;
    position: fixed;
    background: rgba(0, 0, 0, 0.5);
    width: 100%;
    height: 100%;
}
h1{
    color: #03cfb4;
    border: none;
    padding: 0;
}
</style>