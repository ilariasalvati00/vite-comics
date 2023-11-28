<script setup></script>

<template>
    <footer>
        <div class="navbar-footer">
            <div class="navbar-container">
                <div class="content">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <p>DIGITAL COMICS</p>
                </div>
                <div class="content">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <p>DC MERCHANDISE</p>
                </div>
                <div class="content">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                    <p>SUBSCRIPTION</p>
                </div>
                <div class="content">
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                    <p>COMIC SHOP LOCATOR</p>
                </div>
                <div class="content">
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                    <p>DC POWER VISA</p>
                </div>
            </div>
        </div>
        <div class="footer-links">
            <div class="footer-links-col">
                <div class="footer-links-col">
                    <p>DC COMICS</p>
                    <a href="">Characters</a>
                    <a href="">Comics</a>
                    <a href="">Movies</a>
                    <a href="">Tv</a>
                    <a href="">Games</a>
                    <a href="">Videos</a>
                    <a href="">News</a>
                </div>
                <div class="footer-links-col">
                    <p>SHOP</p>
                    <a href="">Shop DC</a>
                    <a href="">Shop DC Collectibles</a>
                </div>
            </div>
            <div class="footer-links-col">
                <p>DC</p>
                <a href="">Terms of Use</a>
                <a href="">Privacy Policy (New)</a>
                <a href="">Ad Choises</a>
                <a href="">Advertising</a>
                <a href="">Jobs</a>
                <a href="">Subscriptions</a>
                <a href="">Talent Workshops</a>
                <a href="">CPSC certificates</a>
                <a href="">Ratings</a>
                <a href="">Shop >Help</a>
                <a href="">Contact Us</a>
            </div>
            <div class="footer-links-col">
                <p>SITES</p>
                <a href="">DC</a>
                <a href="">MAD Magazine</a>
                <a href="">DC Kids</a>
                <a href="">DC Universe</a>
                <a href="">DC Power Visa</a>
            </div>

        </div>
    </footer>
</template>

<style scoped>
footer {
    width: 100%;
    background-image: url(../assets/footer-bg.jpg);
}

.navbar-footer {
    width: 100%;
    background-color: #0282f9;
    padding: 1rem;
}

.navbar-container {
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

.content {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.content>img {
    width: 30px;
    margin: 0 1rem;
}

.content p {
    color: white;
    font-size: 8pt;
}

.footer-links {
    width: 80%;
    margin: auto;
    padding: 2rem;
    display: flex;
    color: white;
    background-image: url("../assets/dc-logo-bg.png");
    background-position: right;
    background-repeat: no-repeat;
}

.footer-links-col {
    width: 30%;
    display: flex;
    flex-direction: column;
}

.footer-links a {
    text-decoration: none;
    color: gray;
}
</style>
