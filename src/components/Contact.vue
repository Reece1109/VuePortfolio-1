<template>
    <section id="contact">
        <h1 class="display-1 my-4 text-center text-white">Contact Page</h1>
        <div class="mb-4">
            <form action="https://formspree.io/f/xjvzpzvw" method="POST">
                <div class="row mb-4 d-flex justify-content-center">
                    <div class="col-4">
                        <div class="form-outline">
                            <input type="text " id="form3Example1" name="fname" class="form-control"
                                placeholder="First-Name " required />
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="form-outline">
                            <input type="text" id="form3Example2" name="lname" class="form-control" placeholder="Surname "
                                required />
                        </div>
                    </div>
                    <div class=" col-8 form-outline mb-4 my-4">
                        <input type="email" id="form3Example3" name="email" class="form-control" placeholder="Email-Address "
                            required />
                    </div>
                    <button type="submit" class="col-7 btn btn-primary btn-block mb-4">
                        Submit
                    </button>
                </div>

            </form>
            <div class="text-center text-white">
                <p>or sign up with:</p>
                <a target="_blank" href="https://www.facebook.com/Reecesimon84/">
                    <button type="button" class="btn btn-primary btn-floating mx-1">
                        <i class="fab fa-facebook-f"></i>
                    </button>
                </a>
                <a target="_blank" href="">
                    <button type="button" class="btn btn-primary btn-floating mx-1">
                        <i class="fa-brands fa-instagram"></i>
                    </button>
                </a>
                <a target="_blank" href="https://twitter.com/ReeceSimon84">
                    <button type="button" class="btn btn-primary btn-floating mx-1">
                        <i class="fab fa-twitter"></i>
                    </button>
                </a>
                <a target="_blank" href="https://github.com/Reece1109">
                    <button type="button" class="btn btn-primary btn-floating mx-1">
                        <i class="fab fa-github"></i>
                    </button>
                </a>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>

</style>
