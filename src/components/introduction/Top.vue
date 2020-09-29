<template>
<div class="background">
    <div class="title-container">
        <div>
            <img class="tri-up" src="../../assets/tri-up.svg" />
            <img class="tri-down" src="../../assets/tri-down.svg" />
            <img class="sat-math" src="../../assets/sat-math.svg" />
        </div>
        <h1 class="title">Learning tailored to your needs.</h1>
        <h3 class="description">
            The world’s first<br />
            <span class="highlight-pink">AI powered</span> tutoring platform.
        </h3>
        <a class="btn btn-danger highlight-pink-bk">GET STARTED</a>
    </div>
    <div class="bottom-navigator">
        <p>The what and why</p>
        <div class="arrow-down"></div>
    </div>
</div>
</template>

<script>
export default {
    name: "Top",
};
</script>

<style scoped>
.background {
    width: 100%;
    height: 1000px;
    background: linear-gradient(249.12deg, #584ec8 0%, #383096 35.3%);
}

.title-container {
    width: 990px;
    padding-top: 20vh;
    margin-left: auto;
    margin-right: auto;
}

.title-container .title {
    font-family: Roboto;
    font-style: normal;
    font-weight: bold;
    font-size: 80px;
    line-height: 97px;

    color: #ffffff;
}

.title-container .description {
    /* The world’s first AI powered tutoring platform. */

    width: 480px;
    height: 137px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 36px;
    line-height: 42px;

    color: #ffffff;
}

.sat-math {
    position: absolute;
    width: 481px;
    height: 646px;
    right: 22%;
    top: 320px;
}

.tri-up {
    position: absolute;
    right: 60px;
    top: 200px;
}

.tri-down {
    position: absolute;
    right: 550px;
    top: 350px;
}

.bottom-navigator {
    margin-left: 30%;
    margin-top: 220px;
    width: fit-content;
}

.bottom-navigator p {
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 24.3103px;
    line-height: 28px;

    color: #ffffff;
}

.arrow-down {
    width: 57px;
    height: 29px;
    margin-top: 26px;
    margin-left: auto;
    margin-right: auto;
    background: url("../../assets/arrow-down.svg");
    background-size: contain;
    background-repeat: no-repeat;
}
</style>
