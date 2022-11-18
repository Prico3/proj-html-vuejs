<script>
export default {
    data() {
        return {
            about: [
                {
                    text: "The company",
                    link: "url"
                },
                {
                    text: "Institutional",
                    link: "url"
                },
                {
                    text: "Social & Events",
                    link: "url"
                },
                {
                    text: "Innovation",
                    link: "url"
                },
                {
                    text: "Enviroment",
                    link: "url"
                },
                {
                    text: "Technology",
                    link: "url"
                },
            ],
            services: [
                {
                    text: "Audit & Assurance",
                    link: "url"
                },
                {
                    text: "Financial Advisory",
                    link: "url"
                },
                {
                    text: "Analytics M&A",
                    link: "url"
                },
                {
                    text: "Middle Marketing",
                    link: "url"
                },
                {
                    text: "Legal Consulting",
                    link: "url"
                },
                {
                    text: "Regulatory Risk",
                    link: "url"
                },
            ],
            support: [
                {
                    text: "Responsability",
                    link: "url"
                },
                {
                    text: "Terms of Use",
                    link: "url"
                },
                {
                    text: "About Cookies",
                    link: "url"
                },
                {
                    text: "Privacy Policy",
                    link: "url"
                },
                {
                    text: "Accessibility",
                    link: "url"
                },
                {
                    text: "Information",
                    link: "url"
                },
            ]
        }
    }
}
</script>

<template>

    <footer>
        <div class="top_footer">
            <div class="ms_container">

                <div class="row row-cols-4">
                    <div class="col">
                        <img src="../assets/img/logo.PNG" alt="">
                        <p>A functional HTML Template for a Corporate & Business.</p>
                        <div class="icons">
                            <i class="fa-solid fa-phone"></i>
                            <span><a href="">+1(305) 1234-5678</a></span>
                        </div>
                        <button>GET IN TOUCH</button>
                    </div>
                    <div class="col">
                        <div class="ms_card">
                            <h4>About</h4>
                            <div v-for="item in about">
                                <i class="fa-solid fa-chevron-right"></i>
                                <a>{{ item.text }}</a>

                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="ms_card">
                            <h4>Services</h4>
                            <div v-for="item in services">
                                <i class="fa-solid fa-chevron-right"></i>
                                <a>{{ item.text }}</a>

                            </div>

                        </div>
                    </div>
                    <div class="col">
                        <div class="ms_card">
                            <h4>Support</h4>
                            <div v-for="item in support">
                                <i class="fa-solid fa-chevron-right"></i>
                                <a>{{ item.text }}</a>

                            </div>
                        </div>
                    </div>

                </div>

            </div>
        </div>
        <div class="bottom_footer">
            <div class="ms_container d-flex justify-content-between">
                <p>Enjoy the low price. We are tracking any intention of piracy.</p>
                <p class="text-end">© 2020 NEXGEN is proudly by <a href="">Codings</a>.</p>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

.top_footer {
    background-color: $shark;
    padding: 3rem 0;

    //debug
    color: white;

    .ms_card {
        background-color: $dark_vibrant;
    }
}

.bottom_footer {
    padding: 1rem 0;
    background-color: black;
    color: $gray_nurse;

    a {
        color: $bluelagoon;
    }

    p {
        margin: 0;
    }
}
</style>