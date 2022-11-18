<script>
export default {}
</script>

<template>
    <section>
        <div class="ms_container d-flex">
            <div class="left_container">
                <p>SEND A MESSAGE</p>
                <h2>Get in <a href="">Touch</a></h2>
                <p>We will respond to you message as sonn as possible.</p>

                <form class="row g-3">
                    <div class="col-6">
                        <label for="inputEmail4" class="form-label"></label>
                        <input type="email" class="form-control" id="inputEmail4">
                    </div>
                    <div class="col-6">
                        <label for="inputPassword4" class="form-label"></label>
                        <input type="password" class="form-control" id="inputPassword4">
                    </div>
                    <div class="col-6">
                        <label for="inputPassword4" class="form-label"></label>
                        <input type="password" class="form-control" id="inputPassword4">
                    </div>
                    <div class="col-6">
                        <select class="form-select">
                            <option selected>Open this select menu</option>
                            <option value="1">One</option>
                            <option value="2">Two</option>
                            <option value="3">Three</option>
                        </select>
                    </div>
                    <div class="col-12">
                        <div class="mb-3">
                            <label for="exampleFormControlTextarea1" class="form-label"></label>
                            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                        </div>
                    </div>
                    <button>SEND</button>
                </form>

            </div>
            <div class="right_container">
                <div class="right_container">
                    <h3>Example Inc.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                    <div class="icons">
                        <i class="fa-solid fa-phone"></i>
                        <span><a href="">+1(305) 1234-5678</a></span>
                    </div>
                    <div class="icons">
                        <i class="fa-solid fa-phone"></i>
                        <span><a href="">+1(305) 1234-5678</a></span>
                    </div>
                    <div class="icons">
                        <i class="fa-solid fa-phone"></i>
                        <span><a href="">+1(305) 1234-5678</a></span>
                    </div>
                    <button>VIEW MAP</button>
                </div>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

.left_container {
    width: 70%;
}

.right_container {
    margin-left: 2rem;
}

.col-6 {
    display: flex;
    align-items: center;
}
</style>