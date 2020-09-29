<template>
<div class="container background d-flex">
    <div class="row">
        <div class="col-6 m-auto">
            <h2 class="text-center highlight-pink">Learn.</h2>
            <p class="text-left ml-auto mr-auto title content" style="width: 424px">
                Students can access free practice tests made up of verified questions
                from our teachers.
            </p>
        </div>
        <div class="col-6 d-flex">
            <img src="../../assets/learner.svg" alt="Learner" />
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "Learn",
};
</script>

<style scoped>
.background {
    width: 100%;
    height: 700px;
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
