<script>
export default {}
</script>

<template>
    <div class="jumbo d-flex align-items-center">

        <div class="ms_container ">

            <div class="wrapper">

                <h1>
                    Ready
                    <a href="">Team</a>
                </h1>
                <p>No matter what your company needs, we will be ready to assist you in yhe best possible way.</p>
                <button>GET IN TOUCH</button>
                <button>READ MORE</button>

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
}
</style>