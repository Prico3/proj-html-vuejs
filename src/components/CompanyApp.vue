<script>
export default {

}
</script>

<template>
    <section class="d-flex">
        <div class="section_left d-flex flex-row-reverse align-items-center">
            <div class="wrapper">
                <p>ABOUT THE NETWORK</p>
                <h2><a href="">The </a>Company</h2>
                <p>
                    For 12 years we have been providing audit and warranty, financial advice, risk advice, taxes and
                    related services to selects clients.
                </p>
                <div class="row row-cols-2">
                    <div class="col">
                        <i class="fa-solid fa-medal"></i>
                        <span>Tradition</span>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col">
                        <i class="fa-solid fa-medal"></i>
                        <span>Tradition</span>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col">
                        <i class="fa-solid fa-medal"></i>
                        <span>Tradition</span>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col">
                        <i class="fa-solid fa-medal"></i>
                        <span>Tradition</span>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <button>GET IN TOUCH</button>
                <button>READ MORE</button>
            </div>
        </div>

        <div class="section_right">
            <img src="../assets/img/about-4.jpg" alt="">
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

section {
    background-color: $woodsmoke;
}

.section_left {
    width: 55%;


    .wrapper {
        // debug
        border: 1px solid green;

        width: 63%;
        color: white;

    }
}

.section_right {
    width: 45%;
}
</style>