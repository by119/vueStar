<template>
<div id="app">
	<img src="./assets/ppmiaologo.jpg">
	<h1>{{ msg }}</h1>
	<h2>小工具集合地</h2>
	<ul>
		<li><a href="#" target="_blank">获取令牌</a></li>
		<li><a href="#" target="_blank">我是路人甲</a></li>
		<li><a href="#" target="_blank">我是路人乙</a></li>
		<li><a href="#" target="_blank">我是路人丙</a></li>
	</ul>
	<h2>vue集合点</h2>
	<ul>
		<li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
		<li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
		<li><a href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
		<li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
		<li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
		<li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
		<li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
		<li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
	</ul>
</div>
</template>

<script>
export default {
	name: 'app',
	data() {
		return {
			msg: '拓展部落'
		}
	}
}
</script>

<style lang="scss">
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

h1,
h2 {
    font-weight: normal;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}
</style>
