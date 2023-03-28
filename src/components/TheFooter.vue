<script>
export default {
    name: "TheFooter"
}
</script>

<template>
    <footer>
        © {{ new Date().getFullYear() }} | Tutti i diritti riservati
    </footer>
</template>

<style scoped>
footer {
    display: flex;
    min-height: 50vh;
    background-image: url("../../public/img/footer-bg.jpg");
   
    border-top: 2px solid burlywood;
    justify-content: center;
    align-items: center;
    background-position: bottom;
    background-size: contain;
    background-repeat: repeat;
}
</style>