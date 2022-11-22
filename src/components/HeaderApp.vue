<script>
export default {
    data() {
        return {
            header: [
                {
                    text: "HOME",
                    link: "#home",
                },
                {
                    text: "SERVICES",
                    link: "#services",
                },
                {
                    text: "ABOUT",
                    link: "#company",
                },
                {
                    text: "PROJECTS",
                    link: "#projects",
                },
                {
                    text: "RESULTS",
                    link: "#results",
                },
            ]
        }
    }
}
</script>

<template>

    <header>

        <div class="ms_container d-flex justify-content-between align-items-center">

            <div class="logo">
                <img src="../assets/img/logo.PNG" alt="">
            </div>

            <div class="nav">
                <ul class="d-flex align-items-center">
                    <li v-for="item in header">
                        <a :href="item.link">{{ item.text }}</a>
                    </li>

                    <li>
                        <button class="btn primary_color">
                            <a href="#form">GET IN TOUCH</a>
                        </button>
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