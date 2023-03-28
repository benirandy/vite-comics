<script>
export default {
    name: "TheHeader"
}
</script>

<template>
    <header>
        <nav>
            <div class="Logo">

            </div>

            <ul class="navbar-links">
                <li><a class="nav-link" href="#">Home</a></li>
                <li><a class="nav-link" href="#">Prodotti</a></li>
                <li><a class="nav-link" href="#">Chi siamo</a></li>
                <li><a class="nav-link" href="#">Contatti</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
.navbar-links {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;
}

.nav-link {
    padding: .5rem 1rem;
    color: black;
    text-decoration: none;
    transition: color .3s ease;
    display: inline-block;
}

.nav-link:hover {
    color: green;
    text-decoration: underline;
}
</style>
