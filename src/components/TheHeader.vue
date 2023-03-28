<script>
export default {
    name: "TheHeader"
}
</script>

<template>
    <header>
        <nav>

            <div>
                <img src="../../public/img/dc-logo.png" alt="Logo-dC">


                <ul class="navbar-links">
                    <li><a class="nav-link" href="#">Character</a></li>
                    <li><a class="nav-link" href="#">Comics</a></li>
                    <li><a class="nav-link" href="#">Movies</a></li>
                    <li><a class="nav-link" href="#">Tv</a></li>
                    <li><a class="nav-link" href="#">Games</a></li>
                    <li><a class="nav-link" href="#">Collectibles</a></li>
                    <li><a class="nav-link" href="#">Videos</a></li>
                    <li><a class="nav-link" href="#">Fans</a></li>
                    <li><a class="nav-link" href="#">News</a></li>
                    <li><a class="nav-link" href="#">Shop</a></li>
                </ul>
            </div>

        </nav>
    </header>
</template>

<style scoped>
header {
    background-color: white;
}

.logo {
    text-align: start;
}

.navbar-links {
    display: flex;
    justify-content: end;
    align-items: end;
    list-style: none;
}

.nav-link {
    padding: 1rem 1.5rem;
    color: black;
    text-decoration: none;
    transition: color .3s ease;
    display: inline-block;
}

.nav-link:hover {
    color: blue;
    text-decoration: underline;
}
</style>
