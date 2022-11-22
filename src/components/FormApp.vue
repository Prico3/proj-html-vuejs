<script>
export default {}
</script>

<template>

    <section id="form">

        <div class="ms_container d-flex">

            <!-- LEFT CONTAINER -->
            <div class="left_container">
                <!-- SMALLER TITLE -->
                <p class="smaller_title">SEND A MESSAGE</p>
                <!-- TITLE -->
                <h2 class="section_title">
                    Get in <a class="primary_section_title" href="">Touch</a>
                </h2>
                <!-- DESCRIPTION -->
                <p class="description_dark">We will respond to you message as soon as possible.</p>

                <!-- FORM -->
                <form class="row g-3">

                    <!-- name -->
                    <div class="col-6">
                        <label for="inputName" class="form-label"></label>
                        <input type="name" class="form-control" id="inputName" placeholder="Name">
                    </div>

                    <!-- email -->
                    <div class="col-6">
                        <label for="inputEmail" class="form-label"></label>
                        <input type="email" class="form-control" id="inputEmail" placeholder="Email">
                    </div>

                    <!-- phone -->
                    <div class="col-6">
                        <label for="inputPhone" class="form-label"></label>
                        <input type="phone" class="form-control" id="inputPhone" placeholder="Phone">
                    </div>

                    <!-- more info -->
                    <div class="col-6">
                        <select class="form-select">
                            <option>More info</option>
                            <option value="#">...</option>
                            <option value="#">...</option>
                            <option value="#">...</option>
                        </select>
                    </div>

                    <!-- text area -->
                    <div class="col-12">
                        <div class="mb-3">
                            <label for="message" class="form-label"></label>
                            <textarea class="form-control" id="message" rows="3" placeholder="Message"></textarea>
                        </div>
                    </div>

                    <!-- send btn -->
                    <button class="btn primary_color">
                        <a href="">SEND</a>
                    </button>

                </form>
                <!-- /FORM -->

            </div>
            <!-- /LEFT CONTAINER -->

            <!-- RIGHT CONTAINER -->
            <div class="right_container">

                <h3>Example Inc.</h3>
                <p class="description_dark">Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                <p class="description_dark">Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>

                <div class="icons">
                    <i class="fa-solid fa-phone"></i>
                    <span><a href="#">+1(305) 1234-5678</a></span>
                </div>

                <div class="icons">
                    <i class="fa-solid fa-envelope"></i>
                    <span><a href="#">hello@example.com</a></span>
                </div>

                <div class="icons">
                    <i class="fa-solid fa-location-dot"></i>
                    <span><a href="#">Main Avenue, 987</a></span>
                </div>

                <button class="btn transparent">
                    <a href="#">VIEW MAP</a>
                </button>

            </div>

            <!-- /RIGHT CONTAINER -->

        </div>

    </section>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

section {
    padding: 4rem 0;
}

// LEFT CONTAINER
.left_container {
    width: 70%;

    input,
    select,
    textarea {
        background-color: $pumice;
        color: #6c7587;
    }

    button {
        width: 100px;
    }
}

// RIGHT CONTAINER
.right_container {
    margin-left: 2rem;

    h3 {
        font-weight: 700;
    }

    .icons {
        color: $bluelagoon;
        margin-bottom: 0.5rem;

        i {
            padding: 8px;
            margin-right: 20px;

            background-color: #6ca0a05b;
            border-radius: 50%;
        }
    }
}

.col-6 {
    display: flex;
    align-items: center;
}
</style>