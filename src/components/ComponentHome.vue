<template>
    <div class="container-div">

        <div class="content-1">
            <h1 class="title">
                Mais que <br>
                uma empresa <br>
                Somos uma <br>
                família
            </h1>
            <div class="container-button">
                <button class="button button-1">
                    COTAR FRETE
                </button>
                <button class="button button-2">
                    RASTREAMENTO
                </button>
            </div>
        </div>
        <div class="content-2">
            <img src="@/assets/caminhao-verm.png" alt="" width="450px">
        </div>

    </div>
</template>

<style scoped>

.title {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color: #cc0000e7;
    font-weight: 600;
    font-size: 70px;
    line-height: 70px;
    text-align: center;
    text-shadow: 0 2px 2px rgba(0, 0, 0, 0.288);
}

.container-div {
    display: flex;
    justify-content: space-evenly;
    padding-top: 35px;
}

.content-1 {
    margin-top: 50px;
}

.container-button {
    margin-top: 40px;
    display: flex;
    justify-content: center;
    gap: 20px
}

.button {
    width: 190px;
    height: 60px;
    border-radius: 30px;
    box-shadow: 0 3px 3px rgba(0, 0, 0, 0.288);
    font-size: 17px;
    font-weight: 500;
}

.button-1 {
    background-color: #cc0000e7;
    color: white;
    border: none;
}

.button-2 {
    background-color: #201F1F;
    color: white;
    border: none;
}

</style>