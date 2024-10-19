<template>

    <div class="second-container container--white">

        <h1 class="container__title container__title--red">
            Ouvidoria
        </h1>
        <form action="" class="container__form">
            <div class="mb-3 form__field">
                <label for="input1" class="form-label form__label">Email address</label>
                <input type="email" class="form-control form__input" id="input1">
            </div>
            <div class="mb-3 form__field">
                <label for="input2" class="form-label form__label">Email address</label>
                <input type="email" class="form-control form__input" id="input2">
            </div>
            <div class="mb-3 form__field">
                <label for="textarea1" class="form-label form__label">Example textarea</label>
                <textarea class="form-control form__textarea" id="textarea1" rows="4"></textarea>
            </div>
            <button class="form__button">
                ENVIAR
            </button>
        </form>
    </div>
</template>

<style scoped>

.second-container {
    width: 50%;
    height: 100%;
    margin-bottom: 30px;
    padding-bottom: 20px
}

.container--white {
    padding: 4% 7% 5% 7%;
}

.container__title--red {
    color: var(--primary-color);
    margin-bottom: 6%;
}

.form__field {
    margin: auto;
}

.form__label {
    color: var(--primary-color);
}

.form__input {
    border-color: var(--dark-gray);
    height: 45px;
}

.form__textarea {
    border-color: var(--dark-gray);
    max-height: 96px;
}

.form__button {
    display: block;
    margin: 6% auto 0 auto !important;
    width: 170px;
    height: 60px;
    border-radius: 30px;
    box-shadow: 0 3px 3px var(--shadow-color);
    font-size: 17px;
    font-weight: 500;
    background-color: var(--primary-color);
    color: white;
    border: none;
}


@media screen and (max-width: 429px) {

    .container__title {
        font-size: 40px;
    }

    .container--white {
        padding: 6% 10% 8% 10%;
    }

    .form__input {
        height: 40px;
    }

    .form__button {
        width: 120px;
        height: 48px;
        font-size: 14px;
    }

}

@media screen and (min-width: 430px) and (max-width: 484px) {

    .container--white {
        padding: 6% 12% 8% 12%;
    }

    .form__input {
        height: 40px;
    }

    .form__button {
        width: 120px;
        height: 48px;
        font-size: 14px;
    }
}

@media screen and (min-width: 485px) and (max-width: 575px) {

    .container__title {
        font-size: 42px;
    }

    .container--white {
        padding: 6% 14% 8% 14%;
    }

    .form__input {
        height: 40px;
    }

    .form__button {
        width: 120px;
        height: 48px;
        font-size: 14px;
    }
}

@media screen and (min-width: 576px) and (max-width: 767px) {

    .container__title {
        font-size: 52px;
    }

    .container--white {
        padding: 8% 14% 10% 14%;
    }

    .form__button {
        width: 150px;
        height: 58px;
        font-size: 16px;
    }
}

@media screen and (max-width: 991px) {

    .second-container {
        width: 100%;
    }

}

@media screen and (min-width: 768px) and (max-width: 991px) {

    .container--white {
        padding: 7% 17% 9% 17%;
    }
}

@media screen and (min-width: 992px) and (max-width: 1199px) {

    .container__title {
        font-size: 52px;
    }

    .form__button {
        width: 150px;
        height: 58px;
        font-size: 16px;
    }
}
</style>