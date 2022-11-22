<script>
export default {}
</script>

<template>

    <header>

        <div class="ms_container d-flex justify-content-between align-items-center">

            <div class="logo">
                <img src="../assets/img/logo.PNG" alt="">
            </div>

            <div class="nav">
                <ul class="d-flex align-items-center">
                    <li><a href="">HOME</a></li>
                    <li><a href="">SERVICES</a></li>
                    <li><a href="">ABOUT</a></li>
                    <li><a href="">PROJECTS</a></li>
                    <li><a href="">RESULTS</a></li>
                    <li>
                        <button class="btn primary_color">GET IN TOUCH</button>
                    </li>
                </ul>
            </div>

        </div>

    </header>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

header {
    padding: 0.5rem 0;
}

img {
    width: 150px;
}

ul {
    margin: 0;

    li {
        margin-left: 0.7rem;
    }
}
</style>