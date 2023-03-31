<script>
export default {
    name: "TheFooter"
}
</script>

<template>
    <div>
        <nav>
            <ul class="footer-bar">
                <img src="/img/buy-comics-digital-comics.png" alt="">
                <li><a class="nav-footer" href="#">Digital Comics</a></li>
                <img src="/img/buy-comics-merchandise.png" alt="">
                <li><a class="nav-footer" href="#">Dc Merchandise</a></li>
                <img src="/img/buy-comics-subscriptions.png" alt="">
                <li><a class="nav-footer" href="#">Subscription</a></li>
                <img src="/img/buy-comics-shop-locator.png" alt="">
                <li><a class="nav-footer" href="#">Comics Shop Locator</a></li>
                <img src="/img/buy-comics-digital-comics.png" alt="">
                <li><a class="nav-footer" href="#">Dc Power Visa</a></li>
            </ul>
        </nav>
    </div>
    <footer>
        <div class="container-col">
            <div class="col1">
                <ul>
                    <h2>DC COMICS</h2>
                    <li>Characters</li>
                    <li>Movies</li>
                    <li>Comics</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <h2>SHOP</h2>
                    <li>Shop Dc</li>
                    <li>Shop Dc Collectible</li>
                </ul>
            </div>
            <div class="col2">
                <ul>
                    <h2>DC COMICS</h2>
                    <li>Characters</li>
                    <li>Movies</li>
                    <li>Comics</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <h2>SHOP</h2>
                    <li>Shop Dc</li>
                    <li>Shop Dc Collectible</li>
                </ul>
            </div>
            <div class="col3">
                <ul>
                    <h2>DC COMICS</h2>
                    <li>Characters</li>
                    <li>Movies</li>
                    <li>Comics</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <h2>SHOP</h2>
                    <li>Shop Dc</li>
                    <li>Shop Dc Collectible</li>
                </ul>
            </div>
        </div>
    </footer>
    <div>
        <ul class="footer-img">
            <div class="btns">
                <button class="my-btn" type="button">
                    <h4> SIGN-UP NOW</h4>
                </button>
            </div>
            <h4>FOLLOW US</h4>
            <li><img src="/img/footer-facebook.png" alt="">
            </li>
            <li><img src="/img/footer-facebook.png" alt=""></li>
            <li><img src="/img/footer-facebook.png" alt=""></li>
            <li><img src="/img/footer-facebook.png" alt=""></li>
            <li><img src="/img/footer-facebook.png" alt=""></li>
        </ul>
    </div>
</template>


<style scoped lang="scss">
@use "../styles/partials/variables" as *;
@use "../styles/partials/mixin";

footer {
    display: flex;
    min-height: 70vh;
    border-top: 2px solid grey;
    justify-content: center;
    align-items: center;
    background-size: contain;
    background-repeat: no-repeat;
}

.footer-bar {
    @include mixin.d-flex-center;
    list-style: none;
    background-color: rgb(32, 92, 175);
    min-height: 15vh;
}

.nav-footer {
    padding: 2rem 1.5rem;
    color: white;
    text-decoration: none;
    display: inline-block;
}

.nav-footer:hover {
    color: red;
    text-decoration: underline;

}

img {
    width: 50px;
}

.container-col {
    width: 900px;
    margin: auto;
    color: white;
    padding-bottom: 240px;
}

.col1,
.col2,
.col3 {
    width: 280px;
    float: left;
    margin: 0.5rem;
}

.container-col ul {
    list-style: none;
}

.styled {
    border: 0;
    line-height: 2.5;
    padding: 0 20px;
    font-size: 1rem;
    text-align: center;
    color: #fff;
    text-shadow: 1px 1px 1px #000;
    border-radius: 10px;
    background-color: grey;
}

.styled:hover {
    background-color: rgba(255, 0, 0, 1);
}

.styled:active {
    box-shadow: inset -2px -2px 3px rgba(255, 255, 255, 0.6), inset 2px 2px 3px rgba(0, 0, 0, 0.6);
}

.footer-img {
    display: flex;
    justify-content: end;
    align-items: center;
    list-style: none;
    background-color: rgb(32, 92, 175);

}
</style>