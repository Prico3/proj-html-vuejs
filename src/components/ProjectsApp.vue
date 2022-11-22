<script>
export default {
    data() {
        return {
            info: [
                {
                    text: "Academic professional program in social media",
                    bg: 'project-1.jpg',
                },
                {
                    text: "President's speech at the annual meeting"
                },
                {
                    text: "International business trip in Shanghai"
                },
                {
                    text: "Technology workshop with education theme"
                },
                {
                    text: "Donation og clothes and food to the partner NGO"
                },
                {
                    text: "Confraternization of the procurment team"
                },
            ]
        }
    },
    computed: {
        bgImg() {
            return `background-image: url("../assets/img/${this.info.bg}");`;

        }
    }
}
</script>

<template>
    <section>
        <div class="ms_container text-center">
            <p class="smaller_title">WE DO MORE FOR EVERYONE</p>
            <h2 class="section_title">Actions & <a class="primary_section_title" href="">Projects</a></h2>
            <ul class="d-flex justify-content-center">

                <li><a href="">ALL</a></li>
                <li><a href="">INSTITUTIONAL</a></li>
                <li><a href="">SOCIAL</a></li>
                <li><a href="">EVENTS</a></li>
                <li><a href="">INNOVATION</a></li>
                <li><a href="">ENVIROMENT</a></li>
                <li><a href="">TECHNOLOGY</a></li>


            </ul>

            <div class="row row-cols-3 g-4">

                <div class="col" v-for="item in info" :style="bgImg">
                    <div class="ms_card">
                        <p>{{ item.text }}</p>

                    </div>
                </div>

            </div>
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

}

.ms_card {
    background-color: bisque;
    border-radius: 15px;
}
</style>