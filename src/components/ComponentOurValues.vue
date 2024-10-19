<template>
    <div class="container main-container">
        <div class="values-container">
            <div class="col-md-3 values-container__info-card">
                <h1 class="values-container__title">
                    MISSÃO
                </h1>
                <p class="values-container__text">
                    There are many variations of passages of Lorem Ipsum available, but the majority have
                </p>
            </div>
            <div class="col-md-3 values-container__info-card">
                <h1 class="values-container__title">
                    VISÃO
                </h1>
                <p class="values-container__text">
                    There are many variations of passages of Lorem Ipsum available, but the majority have
                </p>
            </div>
            <div class="col-md-3 values-container__info-card">
                <h1 class="values-container__title">
                    VALORES
                </h1>
                <p class="values-container__text">
                    There are many variations of passages of Lorem Ipsum available, but the majority have
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped>
.values-container {
    padding: 60px 0 0 0;
}

.values-container {
    display: flex;
    justify-content: space-evenly;
    gap: 40;
}

.values-container__title {
    font-size: 50px;
    font-weight: 700;
    color: #cc0000dc;
    text-shadow: 2px 2px 4px #00000030;
}

.values-container__text {
    font-size: 24px;
    text-shadow: 1px 1px 4px #00000030;
}

@media screen and (max-width: 767px) {

    .values-container {
        flex-direction: column;
    }

    .values-container__info-card {
        padding: 20px 18%;
    }

    .values-container__title {
        font-size: 32px
    }

    .values-container__text {
        font-size: 21px;
        line-height: 36px;
    }
}

@media screen and (min-width: 768px) and (max-width: 991px) {

    .values-container {
        justify-content: space-between;
        gap: 0px;
    }

    .values-container__title {
        font-size: 40px
    }

    .values-container__text {
        font-size: 19px
    }
}

@media screen and (min-width: 992px) and (max-width: 1199px) {

    .values-container__title {
        font-size: 40px
    }
}
</style>