<template>

    <div class="container-fluid container-history">
        <div class="container content-history">

            <div class="content-1 col-md-7">
                <h1 class="text-light display-5 fw-bold title">
                    QUEM SOMOS
                </h1>
                <p class="text-light fs-5 text-center">
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form, by injected humour,
                    or randomised words which don't look even slightly believable.
                    If you are going to use a passage of Lorem Ipsum,
                    you need to be sure there isn't anything embarrassing hidden in the middle of text.
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form, by injected humour,
                    or randomised words which don't look even slightly believable.
                </p>
            </div>
            <img src="@/assets/person.png" alt="foto-funcionário">
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
    color: white
}

.title {
    text-align: center;
    margin-bottom: 20px;
}

@media screen and (max-width: 767px) {

}

</style>