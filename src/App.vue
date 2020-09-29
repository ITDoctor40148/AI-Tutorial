<template>
<div id="app">
    <Top />
    <HowItWorks />
    <Learn />
    <Adapt />
</div>
</template>

<script>
import Top from './components/introduction/Top.vue'
import HowItWorks from './components/introduction/HowItWorks.vue'
import Learn from './components/introduction/Learn'
import Adapt from './components/introduction/Adapt'

export default {
    name: 'App',
    components: {
        Top,
        HowItWorks,
        Learn,
        Adapt
    }
}
</script>

<style>
body {
    margin: 0px;
}

.highlight-pink {
    color: #f663cd;
}

.highlight-pink-bk {
    border-color: #ff3ac7;
    background-color: #f663cd;
}

.highlight-pink-bk:hover {
    border-color: #ff22c0;
    background-color: #ff00b7;
}
</style>
