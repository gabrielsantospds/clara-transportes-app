<template>

    <div class="container-fluid main-container">
        <div class="container ps-5 history-container">

            <div class="history-container__content col-lg-7">
                <h1 class="history-container__info display-2 fw-bold history-container__title">
                    QUEM SOMOS
                </h1>
                <p class="history-container__info history-container__text fs-5 text-center">
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form, by injected humour,
                    or randomised words which don't look even slightly believable.
                    If you are going to use a passage of Lorem Ipsum,
                    you need to be sure there isn't anything embarrassing hidden in the middle of text.
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form, by injected humour.
                </p>
            </div>
            <img src="@/assets/person.png" alt="foto-funcionário" class="history-container__image">
        </div>
    </div>

</template>

<style scoped>

.main-container {
    height: 450px;
    background-color: var(--primary-color);
    padding-top: 50px
}

.history-container {
    height: 350px;
    display: flex;
    flex-direction: row;
    gap: 100px;
}

.history-container__info {
    color: white;
}

.history-container__title {
    text-align: center;
    margin-bottom: 20px;
    text-shadow: 2px 2px 4px var(--shadow-color);
}

.history-container__text {
    text-shadow: 1px 1px 4px var(--shadow-color);
}

@media screen and (max-width: 575px) {

    .main-container {
        display: contents;
    }

    .history-container {
        padding-left: 12px !important;
        padding-bottom: 30px;
        background-color: var(--primary-color);
        height: auto;
    }

    .history-container__content {
        width: 90%;
        margin: 0 auto;
    }

    .history-container__title {
        margin-top: 50px;
        font-size: 40px
    }

    .history-container__text {
        font-size: 15px !important;
        line-height: 37px
    }

    .history-container__image {
        display: none;
    }
}

@media screen and (min-width: 576px) and (max-width: 767px) {

    .main-container {
        display: contents;
    }

    .history-container {
        padding-left: 12px !important;
        padding-bottom: 30px;
        background-color: var(--primary-color);
        height: auto;
    }

    .history-container__content {
        width: 80%;
        margin: 0 auto;
    }

    .history-container__title {
        margin-top: 50px;
        font-size: 45px
    }

    .history-container__text {
        font-size: 16px !important;
        line-height: 37px
    }

    .history-container__image {
        display: none;
    }

}

@media screen and (min-width: 768px) and (max-width: 991px) {

    .main-container {
        display: contents;
    }

    .history-container {
        padding-top: 70px;
        padding-left: 12px !important;
        padding-bottom: 30px;
        background-color: var(--primary-color);
        height: auto;
    }

    .history-container__content {
        width: 80%;
        margin: 0 auto;
    }

    .history-container__image {
        display: none;
    }

    .history-container__title {
        font-size: 70px
    }

    .history-container__text {
        margin-top: 40px;
        line-height: 45px;
    }

}

@media screen and (min-width: 992px) and (max-width: 1199px) {

    .history-container {
        gap: 60px;
        padding-left: 12px !important;
    }

    .history-container__image {
        width: 310px;
        height: 310px;
        margin-top: 25px
    }

    .history-container__title {
        font-size: 60px
    }

    .history-container__text {
        line-height: 30px;
        font-size: 18px !important;
    }

}

@media screen and (min-width: 1200px) {

    .history-container__title {
        margin: 25px 0px
    }

    .history-container__info {
        line-height: 32px;
    }

    .history-container__text {
        margin: 50px 0 0 0
    }
}

</style>