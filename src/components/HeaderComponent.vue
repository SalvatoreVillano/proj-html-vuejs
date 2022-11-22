<template>
    <header>
        <div class="topheader">
            <div class="container d-flex justify-content-between">
                <div class="topheaderleft mt-2">
                    <i class="fa-solid fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00
                </div>
                <div class="topheaderright mt-2">
                    <span><i class="fa-solid fa-phone"></i> +1 (305) 1234-5678</span>
                    <span class="mx-4"><i class="fa-solid fa-envelope"></i> hello@example.com</span>
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter mx-4"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
            </div>
        </div>
        <div class="container d-flex justify-content-between">
            <div>
                <img src="../assets/img/nexgen-logo.svg" class="h-50 w-50 mt-3">
            </div>
            <div class="mainheader">
                <div class="headercontent d-flex align-items-center">
                    <div v-for="(item, index) in headerMenu" :key="index" class="elem px-3 mt-3">
                        {{ item.name }}
                    </div>
                    <button class="mybtn px-3 py-2 mt-3 ms-3">Get in touch</button>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',
    props: {
        headerMenu: Array
    }
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

.topheader {
    background-color: $topheader-bg;
    height: 45px;
}

.headercontent {
    cursor: pointer;

    .elem {
        font-size: 16px;
        color: $black-text;
    }
}
</style>