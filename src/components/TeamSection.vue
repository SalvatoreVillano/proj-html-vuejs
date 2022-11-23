<template>
    <section class="py-5">
        <div class="container my-4 d-flex align-items-center">
            <div class="cardTeam">
                <div>
                    <div class="textSection">We like what we do</div>
                    <p class="secondTextSection fs-1 fw-bold mt-2 text-light"><span
                            class="textBg py-1 px-2 rounded-1">Team</span>
                        of Experts </p>
                    <p class="subText mb-5">Every week we publish content about what is best in the business world.</p>
                </div>
                <div class="d-flex flex-wrap">
                    <div class="myCard d-flex align-items-center mb-4">
                        <img src="../assets/img/team-1.jpg" class="me-4">
                        <div>
                            <p class="teamName">David Cooper</p>
                            <div>
                                <p>Cto & co-founder</p>
                            </div>
                            <div>
                                <i class="fa-brands fa-facebook-f"></i>
                                <i class="fa-brands fa-twitter mx-4"></i>
                                <i class="fa-brands fa-linkedin-in"></i>
                            </div>
                        </div>
                    </div>
                    <div class="myCard d-flex align-items-center mb-4">
                        <img src="../assets/img/team-3.jpg" class="me-4">
                        <div>
                            <p class="teamName">Oliver Jones</p>
                            <div>
                                <p>Chief procurement</p>
                            </div>
                            <div>
                                <i class="fa-brands fa-facebook-f"></i>
                                <i class="fa-brands fa-twitter mx-4"></i>
                                <i class="fa-brands fa-linkedin-in"></i>
                            </div>
                        </div>
                    </div>
                    <div class="myCard d-flex align-items-center mt-4">
                        <img src="../assets/img/team-2.jpg" class="me-4 ">
                        <div>
                            <p class="teamName">Emma Lopez</p>
                            <div>
                                <p>Chief marketing</p>
                            </div>
                            <div>
                                <i class="fa-brands fa-facebook-f"></i>
                                <i class="fa-brands fa-twitter mx-4"></i>
                                <i class="fa-brands fa-linkedin-in"></i>
                            </div>
                        </div>
                    </div>
                    <div class="myCard d-flex align-items-center mt-4">
                        <img src="../assets/img/team-4.jpg" class="me-4">
                        <div>
                            <p class="teamName">T. Johnson</p>
                            <div>
                                <p>Ceo & president</p>
                            </div>
                            <div>
                                <i class="fa-brands fa-facebook-f"></i>
                                <i class="fa-brands fa-twitter mx-4"></i>
                                <i class="fa-brands fa-linkedin-in"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="presidentText">
                <p class="fw-bold fs-5">President Speech</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                <p class="fw-bold">T. Johnson</p>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'TeamSection'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

section {
    background-color: $section-dark-bg;
}

.textBg {
    background-color: $bg-text-dark;
}

.subText {
    font-size: 15px;
}

.cardTeam {
    width: 60%;
}

.myCard {
    width: 50%;

    img {
        width: 25%;
    }
}

.teamName {
    font-weight: bold;
}

.presidentText {
    color: $white-text;
    background-color: $section-text;
    padding: 30px;
    width: 20%;
    font-size: 15px;
}

.cardTeam {
    position: relative;
    left: 150px;
    width: 60%;
}

.presidentText {
    position: relative;
    left: 150px;
    width: 20%;
}
</style>