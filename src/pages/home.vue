<template>
    <div>
        <Navbar />
        <section class="mt-3">
            <h2 class="text-center">HOME CARE</h2>
            <div class="container">
                <div class="row">
                    <div class="col-md-8">
                        <div class="card">
                            <img src="@/assets/icon/parlor.png" />
                            <h5></h5>
                            <h1></h1>
                            <p class="text-center m-5 ">Lorem ipsum dolor sit amet, consetetur sadipscing elitr,

                                sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
                                sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
                                Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
                                Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor
                                invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua...</p>


                            <button type="button" class="btn btn-outline-primary link1">Continue Reading</button>
                            <hr />
                            <div class="d-flex justift-content-between">
                                <p>BY :Irene emade<span>on:16/07/22</span></p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-3">
                        <div class="card text-center mb-3">
                            <img src="@/assets/icon/3.jpg" />
                            <h1>bathhouse</h1>
                            <p class="m-2">
                                Kotha Smith is an enthusiastic and passionate Story Teller. He loves to do different
                                home-made things and share to the world.
                            </p>
                            <div className="social-share d-flex  align-items-center ms-4 gap-1">
                                <p className="s-facebook" href="/"><i className="bi bi-facebook"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-twitter"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-google"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-linkedin"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-instagram"></i></p>

                            </div>
                        </div>
                         <div class="card text-center">
                            <img src="@/assets/icon/8.jpg"/>
                            <h1>caoch</h1>
                            <p class="m-2">
                                Kotha Smith is an enthusiastic and passionate Story Teller. He loves to do different
                                home-made things and share to the world.
                            </p>
                            <div className="social-share d-flex  align-items-center ms-4 gap-1">
                                <p className="s-facebook" href="/"><i className="bi bi-facebook"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-twitter"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-google"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-linkedin"></i></p>
                                <p className="s-facebook" href="/"><i className="bi bi-instagram"></i></p>

                            </div>
                        </div>
                        <div class="card mt-3 text-center m-5">
                            <p class="text-center">GET NEWSLETTER</p>
                            <div>
                                <button class="btn btn-outline border">Your Email Address</button><br />
                                <button type="button" class="btn btn-primary">Subscribe Now</button>
                            </div>
                        </div>

                    </div>

                </div>
            </div>
        </section>
        <section class="mt-">
            <div class="container">
                <div class="row">
                    <div class="col-md-8">
                        <div class="card text-center m-5">
                            <img src="@/assets/icon/5.jpg" />
                            <h5>Travellers</h5>
                            <h1 class="text-center">AN IMAGINARY FOR TRAVELERS</h1>
                            <p class="text-center">Lorem ipsum dolor sit amet, consetetur sadipscing elitr,

                                sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
                                sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
                                Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
                                Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor
                                invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua...</p>


                            <button type="button" class="btn btn-outline-primary link1">Continue Reading</button>
                            <hr />
                            <div class="d-flex justift-content-between">
                                <p>BY :Irene emade<span>on:16/07/22</span></p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-3">
                        <div class="card mb-3 text-cente">
                            <img src="@/assets/icon/comp.png" />
                            <h1 class="m-3">bathhouse</h1>
                            <p class="m-3">
                                Kotha Smith is an enthusiastic and passionate Story Teller. He loves to do different
                                home-made things and share to the world.
                            </p>
                            <div class="d-flex justift-content-between">
                                <p>
                                    ICONS
                                </p>

                            </div>
                        </div>
                         <div class="card text-cente">
                            <img src="@/assets/icon/1.jpg" />
                            <h1 class="m-3">bathhouse</h1>
                            <p class="m-3">
                                Kotha Smith is an enthusiastic and passionate Story Teller. He loves to do different
                                home-made things and share to the world.
                            </p>
                            <div class="d-flex justift-content-between">
                                <p>
                                    ICONS
                                </p>

                            </div>
                        </div>


                    </div>

                </div>
            </div>
        </section>
<Footer/>
    </div>
</template>


<script>
import Navbar from "@/components/navbar.vue"
import Footer from "@/components/footer.vue"
export default {
    name: 'Home-Page',
    components: {
        Navbar,
        Footer
    }

}
</script>


<style>
.link1{
    border: 1px solid #da521e;
    color: #da521e;
    display: inline-block;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 1px;
    padding: 10px 18px;
    align-items: center;
    margin:auto;

}
</style>