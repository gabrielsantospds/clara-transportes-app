<template>
    <div class="container container-values">
        <div class="content-values">
            <div class="col-md-3 block-text">
                <h1 class="title">
                    MISSÃO
                </h1>
                <p class="text">
                    There are many variations of passages of Lorem Ipsum available, but the majority have
                </p>
            </div>
            <div class="col-md-3 block-text">
                <h1 class="title">
                    VISÃO
                </h1>
                <p class="text">
                    There are many variations of passages of Lorem Ipsum available, but the majority have
                </p>
            </div>
            <div class="col-md-3 block-text">
                <h1 class="title">
                    VALORES
                </h1>
                <p class="text">
                    There are many variations of passages of Lorem Ipsum available, but the majority have
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped>
.content-values {
    padding: 60px 0;
}

.content-values {
    display: flex;
    justify-content: space-evenly;
    gap: 40;
}

.title {
    font-size: 50px;
    font-weight: 700;
    color: #cc0000dc;
    text-shadow: 2px 2px 4px #00000030;
}

.text {
    font-size: 24px;
    text-shadow: 1px 1px 4px #00000030;
}

@media screen and (max-width: 767px) {

    .content-values {
        flex-direction: column;
    }

    .block-text {
        padding: 20px 18%;
    }

    .title {
        font-size: 32px
    }

    .text {
        font-size: 21px;
        line-height: 36px;
    }
}

@media screen and (min-width: 768px) and (max-width: 991px) {

    .content-values {
        justify-content: space-between;
        gap: 0px;
    }

    .title {
        font-size: 40px
    }

    .text {
        font-size: 19px
    }
}

@media screen and (min-width: 992px) and (max-width: 1199px) {

    .title {
        font-size: 40px
    }
}
</style>