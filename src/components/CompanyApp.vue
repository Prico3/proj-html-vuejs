<script>
export default {

}
</script>

<template>

    <section id="company" class="d-flex">

        <!-- SECTION LEFT -->
        <div class="section_left d-flex flex-row-reverse align-items-center">

            <div class="wrapper">
                <!-- SMALLER TITLE -->
                <p class="smaller_title">ABOUT THE NETWORK</p>
                <!-- TITLE -->
                <h2 class="section_title"><a class="secondary_section_title" href="">The </a>Company</h2>
                <!-- DESCRIPTION -->
                <p class="description">
                    For 12 years we have been providing audit and warranty, financial advice, risk advice, taxes and
                    related services to selects clients.
                </p>

                <!-- COLS -->
                <div class="row row-cols-2">
                    <div class="col">
                        <i class="fa-solid fa-medal"></i>
                        <span>Tradition</span>
                        <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col">
                        <i class="fa-solid fa-lock"></i>
                        <span>Tradition</span>
                        <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col">
                        <i class="fa-regular fa-pen-to-square"></i>
                        <span>Tradition</span>
                        <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col">
                        <i class="fa-solid fa-graduation-cap"></i>
                        <span>Tradition</span>
                        <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <!-- /COLS -->

                <!-- BUTTONS -->
                <button class="btn primary_color">
                    <a href="#form">GET IN TOUCH</a>
                </button>
                <button class="btn transparent text-light">
                    <a href="">READ MORE</a>
                </button>
                <!-- /BUTTONS -->
            </div>

        </div>
        <!-- /SECTION LEFT -->

        <!-- SECTION RIGHT (added to give bg image) -->
        <div class="section_right">

        </div>
        <!-- /SECTION RIGHT -->

        <!-- DECORATION -->
        <div class="bullets d-flex">
            <img src="../assets/img/bullets.png" alt="">
            <img src="../assets/img/bullets.png" alt="">
        </div>
        <!-- /DECORATION -->
    </section>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

section {
    background-color: $woodsmoke;
    position: relative;

    .bullets {
        position: absolute;
        left: 47%;
        bottom: -25px;

        img {
            width: 50px;
        }

    }
}

// SECTION LEFT
.section_left {
    width: 50%;
    padding: 4rem 1.5rem 4rem 0;


    .wrapper {
        width: 60%;
        color: white;

        .row {
            margin-top: 3rem;

            .col {

                i {
                    color: $fountain_blue;
                    margin-right: 10px;
                }

                span {
                    font-weight: 700;
                }

                p {
                    margin-top: 0.5rem;
                }
            }

        }

        button {
            margin: 0 1rem 0 0;
        }

    }
}


// SECTION RIGHT
.section_right {
    width: 50%;
    background-image: url("../assets/img/about-4.jpg");
    background-repeat: no-repeat;
    background-position: top;
    background-size: cover;
}
</style>