<script>
export default {
    data() {
        return {
            info: [
                {
                    text: "ALL",
                    link: "#",


                },
                {
                    text: "INSTITUTIONAL",
                    link: "#"

                },
                {
                    text: "SOCIAL",
                    link: "#"

                },
                {
                    text: "EVENTS",
                    link: "#"

                },
                {
                    text: "INNOVATION",
                    link: "#"

                },
                {
                    text: "ENVIROMENT",
                    link: "#"

                },
                {
                    text: "TECHNOLOGY",
                    link: "#"

                },
            ]
        }
    },

}
</script>

<template>

    <section id="projects">

        <div class="ms_container text-center">

            <!-- SMALLER TITLE -->
            <p class="smaller_title">WE DO MORE FOR EVERYONE</p>

            <!-- TITLE -->
            <h2 class="section_title">Actions & <a class="primary_section_title" href="">Projects</a></h2>

            <!-- NAV -->
            <ul class="d-flex justify-content-center">
                <li v-for="item in info" class="description_dark"><a :href="item.link">{{ item.text }}</a></li>
            </ul>


            <!-- COLS -->
            <div class="row row-cols-3 g-4">

                <div class="col ">
                    <img class="img_bg" src="../assets/img/project-1.jpg" alt="">
                    <div class="ms_card ">
                        <h6 class="text-light">Academic professional program in social media</h6>
                        <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>

                </div>

                <div class="col">
                    <img class="img_bg" src="../assets/img/project-2.jpg" alt="">
                    <div class="ms_card">
                        <h6 class="text-light">President's speech at the annual meeting</h6>
                        <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

                <div class="col">
                    <img class="img_bg" src="../assets/img/project-3.jpg" alt="">
                    <div class="ms_card">
                        <h6 class="text-light">International business trip in Shanghai</h6>
                        <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

                <div class="col">
                    <img class="img_bg" src="../assets/img/project-4.jpg" alt="">
                    <div class="ms_card">
                        <h6 class="text-light">Technology workshop with education theme</h6>
                        <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

                <div class="col">
                    <img class="img_bg" src="../assets/img/project-5.jpg" alt="">
                    <div class="ms_card">
                        <h6 class="text-light">Donation og clothes and food to the partner NGO</h6>
                        <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

                <div class="col">
                    <img class="img_bg" src="../assets/img/project-6.jpg" alt="">
                    <div class="ms_card">
                        <h6 class="text-light">Confraternization of the procurment team</h6>
                        <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

            </div>
            <!-- COLS -->

        </div>

    </section>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

.ms_container {
    padding: 3rem 0;
}

ul li {
    margin: 3rem 0.3rem;
    font-size: smaller;
    padding: 0.5rem;

    &:hover {
        background-color: #6ca0a05b;
        border-radius: 5px;
    }

}

// COLS
.col {
    position: relative;
    display: flex;
    justify-content: center;


    &:hover {
        p {
            display: block;
        }
    }

    p {
        display: none;
    }

    .img_bg {
        border-radius: 15px;
        filter: contrast(30%);

    }

}

// CARD
.ms_card {
    border-radius: 15px;
    width: 80%;

    position: absolute;
    bottom: 0;

    h6 {
        font-weight: 700;
    }

}
</style>