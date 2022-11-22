<script>
export default {
    data() {
        return {
            about: [
                {
                    text: "The company",
                    link: "#"
                },
                {
                    text: "Institutional",
                    link: "#"
                },
                {
                    text: "Social & Events",
                    link: "#"
                },
                {
                    text: "Innovation",
                    link: "#"
                },
                {
                    text: "Enviroment",
                    link: "#"
                },
                {
                    text: "Technology",
                    link: "#"
                },
            ],
            services: [
                {
                    text: "Audit & Assurance",
                    link: "#"
                },
                {
                    text: "Financial Advisory",
                    link: "#"
                },
                {
                    text: "Analytics M&A",
                    link: "#"
                },
                {
                    text: "Middle Marketing",
                    link: "#"
                },
                {
                    text: "Legal Consulting",
                    link: "#"
                },
                {
                    text: "Regulatory Risk",
                    link: "#"
                },
            ],
            support: [
                {
                    text: "Responsability",
                    link: "#"
                },
                {
                    text: "Terms of Use",
                    link: "#"
                },
                {
                    text: "About Cookies",
                    link: "#"
                },
                {
                    text: "Privacy Policy",
                    link: "#"
                },
                {
                    text: "Accessibility",
                    link: "#"
                },
                {
                    text: "Information",
                    link: "#"
                },
            ]
        }
    }
}
</script>

<template>

    <footer>
        <!-- TOP FOOTER -->
        <div class="top_footer">

            <div class="ms_container">

                <!-- COLS -->
                <div class="row row-cols-4">

                    <div class="col">
                        <img src="../assets/img/logo.PNG" alt="">
                        <p class="description mt-2">A functional HTML Template for a Corporate & Business.</p>

                        <div class="icons">
                            <i class="fa-solid fa-phone"></i>
                            <span><a href="">+1(305) 1234-5678</a></span>
                        </div>

                        <div class="icons">
                            <i class="fa-solid fa-envelope"></i>
                            <span><a href="">hello@example.com</a></span>
                        </div>

                        <div class="icons">
                            <i class="fa-solid fa-location-dot"></i>
                            <span><a href="">Main Avenue, 987</a></span>
                        </div>

                        <button class="btn primary_color">
                            <a href="#form">GET IN TOUCH</a>
                        </button>

                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <h4>About</h4>
                            <div v-for="item in about">
                                <i class="fa-solid fa-chevron-right"></i>
                                <a :href="item.link">{{ item.text }}</a>

                            </div>
                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <h4>Services</h4>
                            <div v-for="item in services">
                                <i class="fa-solid fa-chevron-right"></i>
                                <a :href="item.link">{{ item.text }}</a>

                            </div>

                        </div>
                    </div>

                    <div class="col">
                        <div class="ms_card">
                            <h4>Support</h4>
                            <div v-for="item in support">
                                <i class="fa-solid fa-chevron-right"></i>
                                <a :href="item.link">{{ item.text }}</a>

                            </div>
                        </div>
                    </div>

                </div>
                <!-- /COLS -->

            </div>

        </div>
        <!-- /TOP FOOTER -->

        <!-- BOTTOM FOOTER -->
        <div class="bottom_footer">

            <div class="ms_container d-flex justify-content-between">
                <p class="description">Enjoy the low price. We are tracking any intention of piracy.</p>
                <p class="description text-end">© 2020 NEXGEN is proudly by <a href="#">Codings</a>.</p>
            </div>

        </div>
        <!-- /BOTTOM FOOTER -->

    </footer>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

// TOP FOOTER
.top_footer {
    background-color: #111117;
    padding: 3rem 0;
    color: #bcbebc;

    // ICONS
    .icons {
        font-size: x-small;
        margin-bottom: 1rem;


        i {
            margin-right: 5px;
        }
    }

    // CARDS
    .ms_card {
        background-color: #19191f;
        border-radius: 15px;

        padding: 2rem;
        font-size: x-small;

        h4 {
            color: white;
        }


        i {
            margin-right: 5px;
        }
    }
}

// BOTTOM FOOTER
.bottom_footer {
    padding: 1rem 0;
    background-color: black;
    color: $gray_nurse;

    .description {
        font-size: xx-small;
    }

    a {
        color: $bluelagoon;
    }

    p {
        margin: 0;
    }
}
</style>