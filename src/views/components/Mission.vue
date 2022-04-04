<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container py-0 pb-lg">
            <div class="row justify-content-between align-items-center">
                <div class="col-lg-5 mb-5 mb-lg-0">
                    <h1 class="text-white font-weight-light">Nossa Missão</h1>
                    <p class="lead text-white mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum ad est 
                        quas inventore nostrum autem excepturi voluptate, ducimus odit in. A, culpa dolorem! Fugiat dicta
                        dolore fugit nobis impedit iusto.</p>
                    <router-link to="/about-us" class="btn btn-white mt-4">
                        Ver Mais
                    </router-link>
                </div>
                <div class="col-lg-6 mb-lg-auto">
                    <div class="rounded shadow-lg overflow-hidden transform-perspective-right">
                        <b-carousel id="carousel1"
                                    controls
                                    indicators>
                            <!-- Text slides with image -->
                            <b-carousel-slide img-src="https://ras-upload.s3.amazonaws.com/sites/climatech/img/theme/clima-1.jpg"></b-carousel-slide>
                            <b-carousel-slide img-src="https://ras-upload.s3.amazonaws.com/sites/climatech/img/theme/clima-2.jpg"></b-carousel-slide>
                        </b-carousel>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide
  }
};
</script>
<style>
</style>
