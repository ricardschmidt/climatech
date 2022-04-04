<template>
    <div>
        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-dark shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-3  text-white">Depoimentos
                                    <span>dos nossos clientes.</span>
                                </h1>
                                <p class="lead  text-white">
                                    Estamos sempre trabalhando para trazer o melhor 
                                    aos nossos clientes, e abaixo temos os depoimentos 
                                    de alguns deles.
                                </p>
                                <div class="btn-wrapper">
                                </div>
                            </div>
                            <div class="col-lg-6 row row-grid 
                            justify-content-center
                            align-items-center">
                                 <icon name="fa fa-star" type="success" rounded class="mb-4"></icon>
                                 <icon name="fa fa-star" type="success" rounded class="mb-4"></icon>
                                 <icon name="fa fa-star" type="success" rounded class="mb-4"></icon>
                                 <icon name="fa fa-star" type="success" rounded class="mb-4"></icon>
                                 <icon name="fa fa-star" type="success" rounded class="mb-4"></icon>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <!-- Depositions -->
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 order-lg-1">
                        <card class="border-0 mt-5" hover shadow body-classes="py-5">
                            <div class="d-flex px-3">
                                <div class="col-sm-3 col-6">
                                    <img v-lazy="'https://ras-upload.s3.amazonaws.com/sites/climatech/img/theme/team-4-800x800.jpg'" alt="Circle image"
                                        class="img-fluid rounded-circle shadow" style="width: 150px;">
                                    <small class="d-block text-uppercase text-center font-weight-bold mt-3">Cliente 1</small>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">Awesome Support</h5>
                                    <p>The Arctic Ocean freezes every winter and much of the sea-ice then thaws
                                        every summer, and that process will continue whatever happens.</p>
                                    <a href="#" class="text-success">Learn more</a>
                                </div>
                            </div>
                        </card>
                        <card class="border-0 mt-5" hover shadow body-classes="py-5">
                            <div class="d-flex px-3">
                                <div class="col-sm-3 col-6">
                                    <img v-lazy="'https://ras-upload.s3.amazonaws.com/sites/climatech/img/theme/team-1-800x800.jpg'" alt="Circle image"
                                        class="img-fluid rounded-circle shadow" style="width: 150px;">
                                    <small class="d-block text-uppercase text-center font-weight-bold mt-3">Cliente 2</small>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-primary">Awesome Support</h5>
                                    <p>The Arctic Ocean freezes every winter and much of the sea-ice then thaws
                                        every summer, and that process will continue whatever happens.</p>
                                    <div class="mb-4">
                                        <badge type="primary" rounded>business</badge>
                                        <badge type="primary" rounded>vision</badge>
                                        <badge type="primary" rounded>success</badge>
                                    </div>
                                    <a href="#" class="text-primary">Learn more</a>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-light shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 text-center">
                        <h2 class="display-3">Você gostou de
                            <span class="text-primary">tudo que podemos fazer?</span>
                        </h2>
                        <p class="lead">Caso tenha gostado você pode entrar em contato conosco e solicitar um orçamento,
                            clicando no botão abaixo. Você será redirecionado para nosso whatsapp onde iremos lhe atender
                            da melhor forma possível.
                        </p>
                        <div class="btn-wrapper">
                            <a href="https://api.whatsapp.com/send/?phone=5541984056286&text=Ol%C3%A1%20gostaria%20de%20fazer%20um%20or%C3%A7amento&app_absent=0"
                               class="btn btn-primary mb-3 mb-sm-0">Entre em Contato</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
