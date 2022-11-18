<script>
export default {}
</script>

<template>



    <div class="info">

        <div class="ms_container d-flex justify-content-between align-items-center">

            <div class="left_info">
                <div class="icon">
                    <i class="fa-solid fa-clock"></i>
                    <span>Open Hours: Mon - Sat - 9:00 - 18:00</span>
                </div>
            </div>

            <div class="right_info d-flex">
                <div class="icon">
                    <i class="fa-solid fa-phone"></i>
                    <span>+1 (305) 1234-5678</span>
                </div>
                <div class="icon">
                    <i class="fa-solid fa-envelope"></i>
                    <span>hello@examples.com</span>
                </div>
                <a href="">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="">
                    <i class="fa-brands fa-twitter"></i>
                </a>
                <a href="">
                    <i class="fa-brands fa-linkedin"></i>
                </a>

            </div>

        </div>

    </div>



</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

.info {
    background-color: $dark_vibrant;
    color: $pumice;
    align-items: center;
    padding: 0.5rem 0;
    font-size: xx-small;

    .right_info div,
    a {
        padding-left: 0.5rem;
    }
}
</style>