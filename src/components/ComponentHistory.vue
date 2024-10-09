<template>

    <div class="container-fluid container-history">
        <div class="container ps-5 content-history">

            <div class="content-1 col-lg-7">
                <h1 class="text-light display-2 fw-bold title">
                    QUEM SOMOS
                </h1>
                <p class="text-light text fs-5 text-center">
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form, by injected humour,
                    or randomised words which don't look even slightly believable.
                    If you are going to use a passage of Lorem Ipsum,
                    you need to be sure there isn't anything embarrassing hidden in the middle of text.
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form, by injected humour.
                </p>
            </div>
            <img src="@/assets/person.png" alt="foto-funcionário" class="img">
        </div>
    </div>

</template>

<style scoped>
.container-history {
    height: 450px;
    background-color: #cc0000dc;
    padding-top: 50px
}

.content-history {
    height: 350px;
    display: flex;
    flex-direction: row;
    gap: 100px;
}

.text-light {
    color: white;
}

.title {
    text-align: center;
    margin-bottom: 20px;
    text-shadow: 2px 2px 4px #00000030;
}

.text {
    text-shadow: 1px 1px 4px #00000030;
}

@media screen and (max-width: 575px) {

    .container-history {
        display: contents;
    }

    .content-history {
        padding-left: 12px !important;
        padding-bottom: 30px;
        background-color: #cc0000dc;
        height: auto;
    }

    .content-1 {
        width: 90%;
        margin: 0 auto;
    }

    .title {
        margin-top: 50px;
        font-size: 35px
    }

    .text {
        font-size: 15px !important;
        line-height: 37px
    }

    .img {
        display: none;
    }
}

@media screen and (min-width: 576px) and (max-width: 767px) {

    .container-history {
        display: contents;
    }

    .content-history {
        padding-left: 12px !important;
        padding-bottom: 30px;
        background-color: #cc0000dc;
        height: auto;
    }

    .content-1 {
        width: 80%;
        margin: 0 auto;
    }

    .title {
        margin-top: 50px;
        font-size: 45px
    }

    .text {
        font-size: 16px !important;
        line-height: 37px
    }

    .img {
        display: none;
    }

}

@media screen and (min-width: 768px) and (max-width: 991px) {

    .container-history {
        display: contents;
    }

    .content-history {
        padding-top: 70px;
        padding-left: 12px !important;
        padding-bottom: 30px;
        background-color: #cc0000dc;
        height: auto;
    }

    .content-1 {
        width: 80%;
        margin: 0 auto;
    }

    .img {
        display: none;
    }

    .title {
        font-size: 70px
    }

    .text {
        margin-top: 40px;
        line-height: 45px;
    }

}

@media screen and (min-width: 992px) and (max-width: 1199px) {

    .content-history {
        gap: 60px;
        padding-left: 12px !important;
    }

    .img {
        width: 310px;
        height: 310px;
        margin-top: 25px
    }

    .title {
        font-size: 60px
    }

    .text {
        line-height: 30px;
        font-size: 18px !important;
    }

}

@media screen and (min-width: 1200px) {

    .title {
        margin: 25px 0px
    }

    .text-light {
        line-height: 32px;
    }

    .text {
        margin: 50px 0 0 0
    }
}

</style>