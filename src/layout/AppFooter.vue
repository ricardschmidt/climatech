<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">Obrigado pela preferência!</h3>
                    <h4 class="mb-0 font-weight-light">Entre em contato através das nossas redes sociais.</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                    <a target="_blank" rel="noopener" href="https://www.instagram.com/climatechconforto/"
                       class="btn btn-neutral btn-icon-only btn-instagram btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Nos siga">
                        <i class="fa fa-instagram"></i>
                    </a>
                    <a target="_blank" rel="noopener" 
                       href="https://api.whatsapp.com/send/?phone=5541984056286&text=Ol%C3%A1%20gostaria%20de%20fazer%20um%20or%C3%A7amento&app_absent=0"
                       class="btn btn-neutral btn-icon-only btn-whatsapp btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Whatsapp">
                        <i class="fa fa-whatsapp"></i>
                    </a>
                    <a target="_blank" rel="noopener" 
                       href="https://www.google.com/search?client=ms-android-samsung-gj-rev1&cds=0&hl=pt-BR&v=11.30.9.21.arm&output=search&q=Climatech+Conforto+Ambiental&ludocid=4298680628468219584&lsig=AB86z5Xnd-MHSKthh6-AObIp8smn&kgs=7fc5471212f28d25&shndl=-1&source=sh/x/kp/local&entrypoint=sh/x/kp/local"
                       class="btn btn-neutral btn-icon-only btn-google btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Nos avalie no Google">
                        <i class="fa fa-google"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="mailto:vendas@climatech-pr.com.br"
                       class="btn btn-primary btn-icon-only btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Entre em contato pelo e-mail">
                        <i class="fa fa-envelope"></i>
                    </a>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="https://github.com/ricardschmidt" target="_blank" rel="noopener">
                            <img src="https://ras-upload.s3.amazonaws.com/23rds/23rd-dev-128.png" alt="23rd's Developers">
                        </a>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <router-link to="/about-us" class="nav-link" rel="noopener">Sobre nós</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/blog" class="nav-link" rel="noopener">Blog</router-link>
                        </li>
                         <li class="nav-item">
                            <router-link to="/partiners" class="nav-link" rel="noopener">
                                Parceiros
                            </router-link>
                        </li>
                        <li class="nav-item">
                            <a href="https://github.com/creativetimofficial/argon-design-system/blob/master/LICENSE.md"
                               class="nav-link" target="_blank" rel="noopener">MIT License</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
