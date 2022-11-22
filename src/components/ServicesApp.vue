<script>
export default {}
</script>

<template>

    <section id="services">

        <div class="ms_container">
            <!-- title -->
            <p class="smaller_title">OUR BUSINESS AREAS</p>
            <h2 class="section_title">Excellence in <a class="primary_section_title" href="">Services</a></h2>

            <!-- description -->
            <div class="text d-flex justify-content-between">
                <p class="description_dark p_different m-0">We are leaders in providing consultancy servivces with a set
                    of cutting-edge technologies and a team of a experienced and renowned professionals. These are some
                    options that you can hire.
                </p>
                <button class="btn primary_color">
                    <a href="#">SEE ALL</a>
                </button>
            </div>
            <!-- /description -->


            <!-- <col> -->
            <div class="wrapper mt-4">

                <div class="row row-cols-3 g-4">

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-display"></i>
                            <h6>Audit & Assurance</h6>
                            <p class="description_dark">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-briefcase"></i>
                            <h6>Financial Advisory</h6>
                            <p class="description_dark">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-chart-simple"></i>
                            <h6>Analytics and M&A</h6>
                            <p class="description_dark">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-plane"></i>
                            <h6>Middle Marketing</h6>
                            <p class="description_dark">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-globe"></i>
                            <h6>Legal Consulting</h6>
                            <p class="description_dark">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-inbox"></i>
                            <h6>Regulatory Risk</h6>
                            <p class="description_dark">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                </div>
            </div>
            <!-- </col> -->

        </div>

        <!-- decorations -->
        <div class="bullets d-flex">
            <img src="../assets/img/bullets.png" alt="">
            <img src="../assets/img/bullets.png" alt="">
        </div>
        <!-- /decorations -->

    </section>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

// SECTION
section {
    background-color: $gray_nurse;
    position: relative;


    .bullets {
        position: absolute;
        left: 47%;
        bottom: -25px;
        z-index: 999;

        img {
            width: 50px;
        }

    }

}

// CARD
.ms_container {
    padding: 4rem 0;

    .p_different {
        width: 80%;
    }

    .ms_card {
        padding: 1rem 2rem;

        background-color: white;
        border-radius: 10px;
        position: relative;

        &:hover {
            .i_special {
                background-color: #6ca0a05b;
                border-radius: 50%;
                cursor: pointer;
                padding: 5px;
            }
        }

        h6 {
            margin-top: 0.5rem;
            font-weight: 700;
        }

        .i_special {
            position: absolute;

            top: 30px;
            right: 30px;

            color: $smalt_blue;
        }

        i {
            color: $bluelagoon;
        }
    }

}
</style>