<template>
    <div class="container main-container">

        <div class="text-container">
            <h1 class="text-container__title">
                Mais que <br>
                Uma empresa, <br>
                Somos uma <br>
                Família
            </h1>
            <div class="text-container__button-container">
                <button class="text-container__button text-container__button--red">
                    COTAR FRETE
                </button>
                <button class="text-container__button text-container__button--black">
                    RASTREAMENTO
                </button>
            </div>
        </div>
        <div class="image-container">
            <img src="@/assets/caminhao-verm.png" class="image-container__image" alt="" width="350px">
        </div>

    </div>
</template>

<style scoped>
.main-container {
    display: flex;
    justify-content: space-evenly;
    margin-top: 4%;
}

.text-container {
    padding-top: 2%;
}

.text-container__title {
    font-family: "Playfair Display", serif;
    font-optical-sizing: auto;
    font-style: normal;
    color: var(--primary-color);
    font-weight: 600;
    font-size: 60px;
    line-height: 65px;
    text-align: left;
    text-shadow: 0 2px 2px var(--shadow-color);
}

.text-container__button-container {
    margin-top: 40px;
    display: flex;
    justify-content: flex-start;
    gap: 20px
}

.text-container__button {
    width: 160px;
    height: 56px;
    border-radius: 40px;
    box-shadow: 0 3px 3px var(--shadow-color);
    font-size: 15px;
    font-weight: 500;
}

.text-container__button--red {
    background-color: var(--primary-color);
    color: white;
    border: none;
}

.text-container__button--black {
    background-color: var(--secondary-color);
    color: white;
    border: none;
}

@media screen and (max-width: 469px) {
    
    .main-container {
        padding: 0;
    }

    .text-container__title {
        font-size: 48px;
        line-height: 53px;
    }

    .text-container__button-container {
        flex-direction: column;
        align-items: center;
        gap: 30px;
    }

    .text-container__button {
        width: 146px;
        height: 52px;
        font-size: 14px;
    }

    .image-container__image {
        width: 260px;
    }
}

@media screen and (max-width: 991px) {
    .main-container {
        margin-top: 0;
        flex-direction: column;
        align-items: center;
    }

    .text-container__title {
        text-align: center;
    }

    .text-container__button-container {
        justify-content: center;
        margin: 10% 0;
    }
}

@media screen and (min-width: 470px) and (max-width: 575px) {

    .image-container__image {
        width: 300px;
    }
}

@media screen and (min-width: 576px) and (max-width: 767px) {

    .text-container__title {
        font-size: 65px;
        line-height: 70px;
    }

    .image-container__image {
        width: 350px;
    }

    .text-container__button {
        width: 168px;
        height: 58px;
        font-size: 16px;
    }

}

@media screen and (min-width: 768px) and (max-width: 991px) {

    .text-container__title {
        font-size: 75px;
        line-height: 80px;
    }

    .image-container__image {
        width: 380px;
    }

    .text-container__button-container {
        margin: 50px 0;
        justify-content: center;
    }

    .text-container__button {
        width: 180px;
        height: 62px;
        font-size: 17px;
    }
}

@media screen and (min-width: 1200px) and (max-width: 1399px) {

    .main-container {
        justify-content: center;
        gap: 100px
    }

    .text-container__title {
        font-size: 65px;
        line-height: 68px;
    }

    .image-container__image {
        width: 365px;
    }

    .text-container__button {
        width: 168px;
        height: 58px;
        font-size: 16px;
    }

}

@media screen and (min-width: 1400px) {

    .main-container {
        justify-content: center;
        gap: 130px
    }

    .text-container__title {
        font-size: 70px;
        line-height: 70px;
    }

    .image-container__image {
        width: 380px;
    }

    .text-container__button {
        width: 180px;
        height: 62px;
        font-size: 17px;
    }
}
</style>