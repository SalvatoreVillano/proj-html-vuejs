<template>
    <section class="py-5">
        <div class="container my-4">
            <div class="d-flex align-items-center">
                <div class="newsletterSection mt-5">
                    <div class="textSection">Newsletter</div>
                    <p class="secondTextSection fs-1 fw-bold mt-2"><span class="textBg py-1 px-2 rounded-1">Know</span>
                        First </p>
                    <p class="subText">Follow closely and receive content about our company <br> and the news of the
                        current
                        market.</p>
                </div>
                <div class="inputZone">
                    <input type="text" placeholder="Name">
                    <input class="my-3" type="text" placeholder="Email">
                    <button class="mybtn px-3 py-2">Subscribe</button>
                </div>
            </div>
        </div>
    </section>

</template>

<script>
export default {
    name: 'NewsletterSection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

section {
    background-image: url("../assets/img/bg-1.jpg");
    background-position: center;
    background-repeat: repeat;
    height: 400px;
}

.newsletterSection {

    position: relative;
    left: 200px;
    width: 55%;
}

input {
    width: 80%;
    padding: 10px;
    background-color: rgba(211, 214, 214, 0.5);
    color: $main-text;
    border: 0;
    border-radius: 3px;
    font-size: 13px;

}

.textBg {
    background-color: $bg-text-dark;
}

.secondTextSection {
    color: $white-text
}
</style>