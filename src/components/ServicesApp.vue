<script>
export default {}
</script>

<template>
    <section>

        <div class="ms_container">
            <p class="smaller_title">OUR BUSINESS AREAS</p>
            <h2 class="section_title">Excellence in <a class="primary_section_title" href="">Services</a></h2>

            <div class="text d-flex justify-content-between">
                <p class="description p_different">We are leaders in providing consultancy servivces with a set of
                    cutting-edge
                    technologies and a team
                    of a
                    experienced and renowned professionals. These are some options that you can hire.</p>
                <button>SEE ALL</button>
            </div>

            <div class="wrapper mt-4">

                <div class="row row-cols-3 g-4">

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-display"></i>
                            <h6>Audit & Assurance</h6>
                            <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-briefcase"></i>
                            <h6>Financial Advisory</h6>
                            <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-chart-simple"></i>
                            <h6>Analytics and M&A</h6>
                            <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-plane"></i>
                            <h6>Middle Marketing</h6>
                            <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>
                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-globe"></i>
                            <h6>Legal Consulting</h6>
                            <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>
                    <div class="col">
                        <div class="ms_card">
                            <i class="fa-solid fa-inbox"></i>
                            <h6>Regulatory Risk</h6>
                            <p class="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                            <i class="fa-solid fa-arrow-right i_special"></i>
                        </div>
                    </div>

                </div>
            </div>

        </div>
    </section>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

section {
    background-color: $gray_nurse;
}

.ms_container {
    padding: 4rem 0;

    .p_different {
        color: $gravel;
        width: 80%;
    }

    .ms_card {
        padding: 1rem 2rem;

        background-color: white;
        border-radius: 10px;
        position: relative;

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