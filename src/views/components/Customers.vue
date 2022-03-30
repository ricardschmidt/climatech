<template>
    <section class="section">
        <div class="container">
            <div class="row justify-content-center text-center mb-lg">
                <div class="col-lg-8">
                    <h2 class="display-3">Nossos clientes</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                    <div class="px-4">
                        <img v-lazy="'img/customers/starbucks.jpeg'"
                            class="img-center img-fluid rounded"
                            style="width: 200px;">
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                    <div class="px-4">
                        <img v-lazy="'img/customers/coke.png'"
                            class="img-center img-fluid rounded"
                            style="width: 200px;">
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                    <div class="px-4">
                        <img v-lazy="'img/customers/mc-donalds.png'"
                            class="img-center img-fluid rounded"
                            style="width: 200px;">
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                    <div class="px-4">
                        <img v-lazy="'img/customers/target.svg'"
                            class="img-center img-fluid rounded"
                            style="width: 200px;">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>
</style>
