<template>
<div class="background">
    <div class="arch pt-5">
        <div class="container">
            <div class="row">
                <div class="col-4 justify-content-center d-flex flex-column">
                    <img class="ml-auto mr-auto" src="../../assets/collaborate.svg" />
                    <h3 class="text-center">Collaborate</h3>
                    <p class="text-center">
                        Our students will be able to learn from the country’s finest
                        teachers
                    </p>
                </div>
                <div class="col-4 justify-content-center d-flex flex-column">
                    <img class="ml-auto mr-auto" src="../../assets/intelligent.svg" />
                    <h3 class="text-center">Intelligent</h3>
                    <p class="text-center">
                        We analyze your weaknesses and turn them into strengths
                    </p>
                </div>
                <div class="col-4 justify-content-center d-flex flex-column">
                    <img class="ml-auto mr-auto" src="../../assets/affordable.svg" />
                    <h3 class="text-center">Affordable</h3>
                    <p class="text-center">
                        Ensemble provides personalized tutoring for a fraction of the cost
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div>
        <h2 class="text-center title pt-lg-5">How it works</h2>
        <p class="text-center title">
            Get access to unlimited learning materials for free
        </p>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <img src="../../assets/teacher.svg" alt="Teacher" />
                </div>
                <div class="col-6 m-auto">
                    <h2 class="text-center highlight-pink">Create.</h2>
                    <p class="text-left ml-auto mr-auto title content" style="width: 424px">
                        Teachers can input questions to access rewards such as gift cards
                        and cryptocurrency.
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "HowItWorks",
};
</script>

<style scoped>
.background {
    width: 100%;
    height: 1204px;
    background: linear-gradient(249.12deg, #584ec8 0%, #383096 35.3%);
}

.arch {
    width: 100%;
    height: 318px;
    background: url("../../assets/arch.svg");
    background-repeat: no-repeat;
    background-size: cover;
}

.title {
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 64px;
    line-height: 75px;

    color: #ffffff;
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
