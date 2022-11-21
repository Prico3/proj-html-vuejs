<script>
export default {

}
</script>

<template>
    <section>
        <div class="top_container text-center">
            <div class="ms_container">
                <p class="smaller_title">WHAT ARE WE DOING</p>
                <h2 class="section_title"><a class="secondary_section_title" href="">Results</a> in Numbers</h2>
                <div class="row row-cols-4 mt-5">
                    <div class="col">
                        <h4>128</h4>
                        <p>Certifications</p>
                    </div>
                    <div class="col">
                        <h4>230</h4>
                        <p>Employees</p>
                    </div>
                    <div class="col">
                        <h4>517</h4>
                        <p>Costumers</p>
                    </div>
                    <div class="col">
                        <h4>94</h4>
                        <p>Countries</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="bottom_container">
            <div class="ms_container">
                <div class="row row-cols-6 text-center">
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-2.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-3.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-4.png" alt="">
                    </div>
                    <div class="col">
                        <img class="special" src="../assets/img/logo-5.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
                    </div>

                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

section {
    padding: 3rem 0;

    .top_container {
        background-image: url("../assets/img/bg-7.jpg");
        background-size: cover;
        background-repeat: no-repeat;

        color: white;
        padding: 5rem 0;

        .col {
            h4 {
                color: $fountain_blue;
                font-weight: 700;
            }

            p {
                font-weight: 700;
            }
        }
    }

    .bottom_container {
        padding: 3rem 0;
        background-color: $woodsmoke;

        img {
            width: 100px;
            filter: invert(92%) sepia(9%) saturate(251%) hue-rotate(68deg) brightness(110%) contrast(89%);
        }

        .special {
            width: 60px;
        }
    }
}
</style>