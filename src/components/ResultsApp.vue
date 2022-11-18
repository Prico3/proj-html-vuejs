<script>
export default {

}
</script>

<template>
    <section>
        <div class="top_container text-center">
            <div class="ms_container">
                <p>WHAT ARE WE DOING</p>
                <h2><a href="">Results</a> in Numbers</h2>
                <div class="row row-cols-4">
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
                <div class="row row-cols-6">
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
                    </div>
                    <div class="col">
                        <img src="../assets/img/logo-1.png" alt="">
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
        color: white;
        padding: 3rem 0;
    }

    .bottom_container {
        padding: 3rem 0;
        background-color: $woodsmoke;
    }
}
</style>