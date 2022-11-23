<template>
    <section class="py-5">
        <div class="container my-4">
            <div class="d-flex justify-content-between">
                <div class="newsSection">
                    <div class="textSection">Our editorial Content</div>
                    <p class="secondTextSection fs-1 fw-bold mt-2">Latest <span
                            class="textBg py-1 px-2 rounded-1">News</span>
                    </p>
                    <p class="subText">Every week we publish content about what is best in the business world.</p>
                </div>
                <div>
                    <button class="mybtn mt-3 me-2 px-3 py-2">See all</button>
                </div>
            </div>
            <div class="d-flex justify-content-center mt-4">
                <div class="newsCard">
                    <img src="../assets/img/news-1.jpg">
                    <div class="textImg d-flex align-items-end text-center">
                        <p class="fw-bold">Increasing creativity is possible for everyone</p>
                    </div>
                </div>
                <div class="newsCard mx-5">
                    <img src="../assets/img/news-2.jpg">
                    <div class="textImg d-flex align-items-end text-center">
                        <p class="fw-bold">Increasing creativity is possible for everyone</p>
                    </div>
                </div>
                <div class="newsCard">
                    <img src="../assets/img/news-3.jpg">
                    <div class="textImg d-flex align-items-end text-center">
                        <p class="fw-bold">Increasing creativity is possible for everyone</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'NewsSection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

.secondTextSection {
    color: $topheader-bg;
}

.newsSection {
    position: relative;
    left: 150px;
    width: 60%;
}

.textBg {
    color: $button-bg;
    background-color: $bg-text-light;
}

.subText {
    font-size: 15px;
}

.newsCard {
    width: 20%;
    position: relative;

    img {
        width: 100%;
    }

}

.mybtn {
    position: relative;
    right: 100px;
    top: 60px;
}

.textImg {
    font-size: 18px;
    color: $white-text;
    background-color: rgba(0, 0, 0, 0.363);
    width: 100%;
    height: 100%;
    position: absolute;
    bottom: 0;

}
</style>