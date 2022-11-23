<template>
    <section class="py-5 text-center">
        <div class="container">
            <div>
                <div class="textSection">How it works in practice</div>
                <p class="secondTextSection fs-1 fw-bold mt-2"><span class="textBg py-1 px-2 rounded-1">Process</span>
                    Management </p>
                <p class="subText">We work with innovative methodologies to ensure that the entire reformatting process
                    is done form
                    start to finish as planned.</p>
            </div>
        </div>
        <div class="container-fluid position-relative">
            <div class="lineProcess"></div>
            <div class="container d-flex">
                <div class="processCard">
                    <span class="circleProcess">01</span>
                    <p class="fw-bold fs-5 mt-3">Collection of information</p>
                    <p class="subText">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
                <div class="processCard">
                    <span class="circleProcess">02</span>
                    <p class="fw-bold fs-5 mt-3">Strategic planning</p>
                    <p class="subText">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
                <div class="processCard">
                    <span class="circleProcess">03</span>
                    <p class="fw-bold fs-5 mt-3">Assignment of responsibilities</p>
                    <p class="subText">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
                <div class="processCard">
                    <span class="circleProcess">04</span>
                    <p class="fw-bold fs-5 mt-3">Formatting process</p>
                    <p class="subText">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
                <div class="processCard">
                    <span class="circleProcess">05</span>
                    <p class="fw-bold fs-5 mt-3">Continuity formalization</p>
                    <p class="subText">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ProcessSection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;


.secondTextSection {
    color: $topheader-bg;
}

.textBg {
    color: $button-bg;
    background-color: $bg-text-light;
}

.lineProcess {
    position: absolute;
    background-color: $bg-text-light;
    height: 5px;
    width: 99%;
    z-index: 1;
    top: 15px;
}


.circleProcess {
    display: inline-block;
    border-radius: 70%;
    width: 40px;
    height: 40px;
    line-height: 40px;
    background-color: $bg-text-light;
    color: $section-text;
    font-weight: bold;
}

.processCard {
    width: calc(100% / 5);
    z-index: 2;
}

.fw-bold {
    color: $black-text;
}

.subText {
    font-size: 13px;
}
</style>


