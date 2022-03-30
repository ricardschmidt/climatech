<template>
    <div>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">404... Página não encontrada</h2>
                        <p class="lead text-white">Esta página não foi encontrada, você pode retorar ao início clicando no botão a baixo.</p>
                    </div>
                </div>
                <div class="text-center">
                    <router-link to="/" rel="noopener" class="btn btn-neutral btn-icon">
                        <span class="btn-inner--icon">
                            <i class="fa fa-home mr-2"></i>
                        </span>
                        <span class="nav-link-inner--text">Voltar para Home</span>
                    </router-link>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: "pageNotFound",
  components: {}
};
</script>
