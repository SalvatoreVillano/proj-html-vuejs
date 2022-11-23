<template>
    <section class="py-5">
        <div class="container">
            <div class="d-flex justify-content-between align-items-end">
                <div class="serviceSection">
                    <div class="textSection">Our business areas</div>
                    <p class="secondTextSection fs-1 fw-bold mt-2">Excellence in <span
                            class="textBg py-1 px-2 rounded-1">Services</span> </p>
                    <p class="subText">We are leaders in providing consultancy services with a set of cutting-edge
                        technologies and a
                        team of experienced and renowned professionals. These are some options that you can hire.</p>
                </div>
                <div>
                    <button class="mybtn mt-3 me-2 px-3 py-2">See all</button>
                </div>
            </div>
            <div class="d-flex flex-wrap justify-content-between">
                <div class="cardService mt-4">
                    <div class="d-flex justify-content-between">
                        <i class="fa-solid fa-network-wired mx-2 my-2"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                    <p class="fw-bold fs-5 mt-3 text-dark">Audit & Assurance</p>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                </div>
                <div class="cardService mt-4">
                    <div class="d-flex justify-content-between">
                        <i class="fa-solid fa-briefcase mx-2 my-2"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                    <p class="fw-bold fs-5 mt-3 text-dark">Financial Advisory</p>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                </div>
                <div class="cardService mt-4">
                    <div class="d-flex justify-content-between">
                        <i class="fa-solid fa-chart-simple mx-2 my-2"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                    <p class="fw-bold fs-5 mt-3 text-dark">Analytics and M&A</p>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                </div>
                <div class="cardService mt-4">
                    <div class="d-flex justify-content-between">
                        <i class="fa-solid fa-plane-up mx-2 my-2"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                    <p class="fw-bold fs-5 mt-3 text-dark">Middle Marketing</p>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                </div>
                <div class="cardService mt-4">
                    <div class="d-flex justify-content-between">
                        <i class="fa-solid fa-earth-europe mx-2 my-2"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                    <p class="fw-bold fs-5 mt-3 text-dark">Legal Consulting</p>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                </div>
                <div class="cardService mt-4">
                    <div class="d-flex justify-content-between">
                        <i class="fa-solid fa-box mx-2 my-2"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                    <p class="fw-bold fs-5 mt-3 text-dark">Regulatory Risk</p>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'ServicesSection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

section {
    background-color: $section-light-bg;

}

.container {
    position: relative;
    left: 50px;
    width: 60%;
}

.secondTextSection {
    color: $topheader-bg;
}

.textBg {
    color: $button-bg;
    background-color: $bg-text-light;
}

.subText {
    font-size: 15px;
}

.serviceSection {
    width: 60%;
}

.cardService {
    width: 30%;
    padding: 15px;
    background-color: $white-text;
    border-radius: 5px;

    i {
        color: $section-text;
        font-size: 30px;
    }
}
</style>