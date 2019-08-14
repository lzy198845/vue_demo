<template>
    <div id="app">
        <img width="25%" src="./assets/logo.png">
        <!-- <HelloWorld msg="Hello Vue in CodeSandbox!"/> -->
        <demo1 msg="123"/>
        <div>反应不是很快，是因为网络的原因吗</div>
        <div>还是浏览器的原因</div>
        <div>只能做小规模的测试，不便于用于整体项目的开发</div>
    </div>
</template>

<script>
import demo1 from "./components/demo1";
import HelloWorld from "./components/HelloWorld";

export default {
    name: "App",
    components: {
        HelloWorld,
        demo1
    }
};
</script>

<style>
#app {
    font-family: "Avenir", Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
