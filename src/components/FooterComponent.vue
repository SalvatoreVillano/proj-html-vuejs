<template>
    <footer class="py-5">
        <div class="myfooter">
            <div class="container d-flex justify-content-between">
                <div class="footerCard">
                    <div class="logoZone">
                        <img src="../assets/img/nexgen-logo.svg">
                    </div>
                    <p class="mt-4">A Functional HTML Template for Corporate & Business.</p>
                    <p><i class="fa-solid fa-phone"></i> +1 (305) 1234-5678</p>
                    <p class="mt-3"><i class="fa-solid fa-envelope"></i> hello@example.com</p>
                    <p><i class="fa-solid fa-location-dot"></i> Main Avenue, 987</p>
                    <button class="mybtn mt-2 me-2 px-3 py-2">Get in touch</button>
                </div>
                <div class="footerCard myCard" v-for="(item, index) in footerMenu" :key="index">
                    <p class="fw-bold fs-3">{{ item.section }}</p>
                    <div v-for="(elem, nameIndex) in item.elem" :key="nameIndex">
                        <p>{{ elem.name }}</p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterComponent',
    props: {
        footerMenu: Array
    }
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

footer {
    background-color: $section-dark-bg;

}

.footerCard {
    width: 15%;
}

.myCard {
    background-color: #19191F;
    border-radius: 10px;
    padding: 30px;
}
</style>