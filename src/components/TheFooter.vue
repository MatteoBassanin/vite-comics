<template>
    <div class="footer_wrapper">
        <div class="inner_wrapper w_80_auto d_flex space_between">
            <div class="left_side">
                <div class="list_wrapper d_flex space_between">
                    <div class="first col">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h3>SHOP</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectables</a></li>
                        </ul>
                    </div>
                    <div class="second col">
                        <h3>DC</h3>
                        <ul>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                    <div class="third col">
                        <h3>SITES</h3>
                        <ul>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                    </div>
                </div>
            </div>
            <div class="right_side p_relative">
                <img class="big_logo p_absolute" src="public/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<script></script>

<style scoped>
.footer_wrapper {
    background-image: url("/img/footer-bg.jpg");
    height: 400px;

}

.right_side {
    background-image: url("/img/dc-logo-bg.png");
    z-index: 1;
}

ul {
    list-style: none;
}

.col {
    padding: 20px;
}

a {
    text-decoration: none;
    color: grey;
}

h3 {
    color: white;
}

.big_logo {
    right: 50px;

    top: -95px;
}
</style>