<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="https://ras-upload.s3.amazonaws.com/sites/climatech/img/brand/climatech-vertical-white.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="https://ras-upload.s3.amazonaws.com/sites/climatech/img/brand/climatech-vertical.png" alt="logo">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text">Fotos e Depoimentos</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <router-link to="/images"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <i class="fa fa-film"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">Portifólio</h6>
                                <p class="description d-none d-md-inline-block mb-0">Aqui estão nossas fotos e vídeos.</p>
                            </div>
                        </router-link>
                        <router-link to="/depositions"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">Depoimentos</h5>
                                <p class="description d-none d-md-inline-block mb-0">O que os nossos clientes tem a falar.</p>
                            </div>
                        </router-link>
                    </div>
                </base-dropdown>
                <router-link to="/about-us" class="nav-link">Sobre Nós</router-link>
                <base-dropdown tag="li" class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">Outros</span>
                    </a>
                    <router-link to="/info" class="dropdown-item">O que Fazemos?</router-link>
                    <router-link to="/blog" class="dropdown-item">Blog</router-link>
                    <router-link to="/partners" class="dropdown-item">Parceiros</router-link>
                    <router-link to="/contact" class="dropdown-item">Contato</router-link>
                </base-dropdown>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.instagram.com/climatechconforto/"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://api.whatsapp.com/send/?phone=5541984056286&text=Ol%C3%A1%20gostaria%20de%20fazer%20um%20or%C3%A7amento&app_absent=0" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                <span class="btn-inner--icon">
                  <i class="fa fa-whatsapp mr-2"></i>
                </span>
                        <span class="nav-link-inner--text">Entre em Contato</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
