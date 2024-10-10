<template>
    <div class="container container-footer">
        <footer class="row row-cols-1 row-cols-sm-2 row-cols-md-4 py-5 my-5 border-top content-footer">
            <div class="col mb-3">
                <a href="/" class="d-flex align-items-center mb-3 link-body-emphasis text-decoration-none">
                    <img src="@/assets/brand-red-black-black.png" alt="" width="160px" class="img">
                </a>
            </div>
            <div class="col mb-3"></div>
            <div class="col mb-3">
                <h5>LINKS ÚTEIS</h5>
                <ul class="nav flex-column">
                    <li class="nav-item mb-2">
                        <a href="#" class="nav-link p-0 text-body-secondary">
                            Quem Somos
                        </a>
                    </li>
                    <li class="nav-item mb-2">
                        <a href="#" class="nav-link p-0 text-body-secondary">
                            Fale Conosco
                        </a>
                    </li>
                </ul>
            </div>
            <div class="col mb-3">
                <h5>SERVIÇOS</h5>
                <ul class="nav flex-column">
                    <li class="nav-item mb-2">
                        <a href="#" class="nav-link p-0 text-body-secondary">
                            Cotação
                        </a>
                    </li>
                    <li class="nav-item mb-2">
                        <a href="#" class="nav-link p-0 text-body-secondary">
                            Rastreamento
                        </a>
                    </li>
                </ul>
            </div>
        </footer>
    </div>
</template>

<style scoped>
.container-footer {
    padding: 0 60px;
}

.content-footer {
    margin-bottom: 0 !important;
}

@media screen and (max-width: 767px) {

    .img {
        width: 145px !important;
    }

}
</style>