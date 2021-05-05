<template>
    <div class="HomeMiddleCardsClass">
    <b-row>
        <!-- Col 1 -->
        <b-col>
        <b-card
            title="Trees"
            img-src="../assets/JapaneseMaple.png"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 25rem; height: 35rem;"
            class="mb-2"
        >
            <b-card-text>
            Trees? You bet your ass we got trees. I cut down the whole fucking rainforest!
            </b-card-text>

            <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
        </b-col>

        <!-- Col 2 -->
        <b-col>
        <b-card
            title="Shrubs"
            img-src="../assets/boxwood shrub.png"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 25rem; height: 35rem;"
            class="mb-2"
        >
            <b-card-text>
            Shrubba bubba Shrubba Bubba Shrubba Bubba
            </b-card-text>

            <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
        </b-col>

        <!-- Col 3 -->
        <b-col>
        <b-card
            title="Perennials"
            img-src="../assets/perennials.png"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 25rem; height: 35rem;"
            class="mb-2"
        >
            <b-card-text>
            Perennials are like annuals but they dont die POG
            </b-card-text>

            <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
        </b-col>
    </b-row>
    </div>
</template>


<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Amatic+SC&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

.HomeMiddleCardsClass{
    padding-right: 30px;
    padding-left: 30px;
    padding-bottom: 30px;
    padding-top: 30px;
    background-color: #fff;
}

.card{
    display:block;
    margin-left: auto;
    margin-right: auto;
    background-color: #F4E8E8;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.h4, h4 {
    font-size: 4rem;
    font-family: 'Amatic SC', cursive;
    font-weight: 900;
    color: #666465;
}

p {
    margin-top: 0;
    margin-bottom: 1rem;
    font-family: 'Roboto', sans-serif;
    font-size: 1.3rem;
    color: #666465;
}

</style>