<template>
<div class="background">
    <div class="container">
        <div class="row d-flex" style="height: 100%">
            <div class="col-6 d-flex">
                <img src="../../assets/adapter.svg" alt="Learner" />
            </div>
            <div class="col-6 m-auto">
                <h2 class="text-center highlight-pink">Adapt.</h2>
                <p class="text-left ml-auto mr-auto title content" style="width: 424px">
                    Our algorithm analyzes the student's weaknesses and then assigns a
                    personalized test.
                </p>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "Adapt",
};
</script>

<style scoped>
.background {
    width: 100%;
    height: 880px;
    background: linear-gradient(249.12deg,
            #584ec8 0%,
            #3f37a1 35.3%,
            #383096 35.3%);
}

.title {
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 64px;
    line-height: 75px;

    color: #000000;
}

p.title {
    font-size: 15px;
    line-height: 18px;
}

h2 {
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 96px;
    line-height: 112px;
}

p.title.content {
    font-size: 30px;
    line-height: 35px;
}
</style>
