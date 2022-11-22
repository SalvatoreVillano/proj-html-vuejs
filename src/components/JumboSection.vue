<template>
    <section>
        <div class="container d-flex justify-content-end align-items-center">
            <div class="jumbo">
                <div class="textSection">Fusion & Acquisitions</div>
                <p class="display-4 fw-bold secondTextSection">Insurance <br> Consulting</p>
                <div class="inputzone">
                    <input class="mt-1 me-3" type="text" placeholder="Name">
                    <input type="text" placeholder="Email">
                    <input class="mt-3 me-3" type="text" placeholder="Phone">
                    <select>
                        <option value="0">More Info</option>
                    </select>
                </div>
                <button class="mybtn mt-3 me-2 px-3 py-2">Get in Touch</button>
                <button class="secondbtn px-3 py-2">Read More</button>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'JumboSection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

section {
    background-image: url('../assets/img/bg-6.jpg');
    background-position: 30%;
    height: 750px;
    margin-top: -70px;

    .container {
        height: 80%;
    }
}

.jumbo {
    width: 50%;
}

.secondTextSection {
    color: $topheader-bg;
    font-weight: 400;
    -webkit-text-stroke: 1px $topheader-bg;
}

input,
select {
    width: 35%;
    padding: 10px;
    background-color: rgb(211, 214, 214);
    color: $main-text;
    border: 0;
    border-radius: 3px;
    font-size: 13px;
}
</style>