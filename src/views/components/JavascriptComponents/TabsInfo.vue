<template>
    <div class="row justify-content-center">
        <div class="col-lg-10">
            <!-- Tabs with icons -->
            <tabs fill class="flex-column flex-md-row">
                <card shadow>
                    <tab-pane key="tab1">
                        <template slot="title">
                            <i class="ni ni-cloud-upload-96 mr-2"></i>Instalação
                        </template>
                        <p><strong>Qual o prazo de instalação?</strong></p>
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache
                            cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro
                            keffiyeh dreamcatcher synth.</p>
                        <p><strong>Quanto tempo tenho de garantia?</strong></p>
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse.</p>
                    </tab-pane>
                    <tab-pane key="tab2">
                        <template slot="title">
                            <i class="ni ni-bell-55 mr-2"></i>Manutenção
                        </template>
                        <p><strong>De quanto em quanto tempo devo fazer a manutenção?</strong></p>
                        <p class="description">Cosby sweater eu banh mi, qui irure terry richardson ex
                            squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan
                            american apparel, butcher voluptate nisi qui.</p>
                    </tab-pane>

                    <tab-pane key="tab3">
                        <template slot="title">
                            <i class="ni ni-calendar-grid-58 mr-2"></i>Agendamento
                        </template>
                        <p><strong>Como agendo uma visita?</strong></p>
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache
                            cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro
                            keffiyeh dreamcatcher synth.</p>
                    </tab-pane>
                </card>
            </tabs>
        </div>
    </div>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  components: {
    Tabs,
    TabPane
  }
};
</script>
<style>
</style>
