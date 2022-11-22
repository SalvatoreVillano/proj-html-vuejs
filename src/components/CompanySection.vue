<template>
    <section class="py-5">
        <div class="container d-flex my-4">
            <div class="companySection">
                <div class="textSection">About the network</div>
                <p class="secondTextSection fs-1 fw-bold mt-2"><span class="textBg py-1 px-2 rounded-1">The</span>
                    Company </p>
                <p class="subText mt-2"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aut assumenda laborum
                    odio quis ut pariatur consequuntur ratione.
                </p>
                <p class="subText"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aut assumenda laborum odio
                    quis ut pariatur consequuntur ratione.
                </p>
            </div>
            <div class="listElem row row-cols-2 mt-4">
                <div class="fw-bold elem col fs-5"> <i class="icon fa-solid fa-award"></i> Tradition
                    <p class="subText mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                </div>
                <div class="fw-bold col fs-5"> <i class="icon fa-solid fa-lock"></i> Security
                    <p class="subText mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                </div>
                <div class="fw-bold elem col fs-5"> <i class="icon fa-regular fa-pen-to-square"></i> Certificate
                    <p class="subText mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                </div>
                <div class="fw-bold col fs-5"> <i class="icon fa-solid fa-graduation-cap"></i> Expertise
                    <p class="subText mt-2">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                </div>
            </div>

        </div>
    </section>
</template>

<script>
export default {
    name: 'CompanySection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

section {
    background-color: $section-dark-bg;
    color: $white-text;
}


.textBg {
    background-color: $bg-text-dark;
}

.icon {
    color: $button-bg;
}

.subText {
    font-size: 11px;
    width: 50%;
    font-weight: 400;

}

.listElem {
    width: 60%;
    position: relative;
    left: 10px;

    .elem {
        margin-right: -100px;
    }
}

.companySection {
    position: relative;
    left: 150px;
    width: 60%;
}
</style>