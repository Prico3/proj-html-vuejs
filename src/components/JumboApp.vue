<script>
export default {}
</script>

<template>

    <section id="home"></section>

    <div class="jumbo d-flex align-items-center">

        <div class="ms_container ">

            <div class="wrapper">
                <!-- title -->
                <h1 class="section_title">
                    Ready <a class="primary_section_title" href="">Team</a>
                </h1>
                <!-- description -->
                <p class="description_dark">No matter what your company needs, we will be ready to assist you in the
                    best possible way.
                </p>

                <!-- buttons -->
                <button class="btn primary_color">
                    <a href="#form">GET IN TOUCH</a>
                </button>

                <button class="btn transparent">
                    <a href="#">READ MORE</a>
                </button>
                <!-- /buttons -->

            </div>

        </div>

    </div>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

.jumbo {
    background-image: url("../assets/img/bg-parallax.png");
    background-repeat: no-repeat;
    background-size: 100% * 2;
    background-position: center;

    height: 550px;
}

.wrapper {
    margin: auto;
    width: 35%;
    text-align: center;

    button {
        margin: 0.5rem;
    }
}
</style>