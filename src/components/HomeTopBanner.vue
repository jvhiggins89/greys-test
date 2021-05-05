<template>
    <div class="HomeBannerDiv">
        <b-jumbotron>
        <template #header>Welcome to Gray's Nursery</template>

        <template #lead>
            Southern Maryland's premire nursery, providing you better prices than other
            local nurseries, and better product than home improvement stores. Come by and
            see what we can provide for your next gardening project.
        </template>

        <hr class="my-4">
        </b-jumbotron>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Amatic+SC&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

.jumbotron{
    background-color: #F4E8E8;
}

.HomeBannerDiv{
    padding-top: 30px;
    padding-left: 30px;
    padding-right: 30px;
}

.display-3 {
    font-size: 7rem;
    font-family: 'Amatic SC', cursive;
    font-weight: bolder;
    line-height: 1.2;
    color: #506369;
}

.lead {
    font-size: 1.75rem;
    font-weight: 300;
    font-family: 'Roboto', sans-serif;
    color: #506369;
}
</style>