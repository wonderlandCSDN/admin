<template>
<div id="app">
	<router-view v-if="isRouterAlive"></router-view>
</div>
</template>

<script>
export default {
	name: 'App',
	/* provide () {
		return {
			reload: this.reload
		}
	}, */
	data () {
		return {
			isRouterAlive: true,
		}
	},
	mounted(){},
	methods: {
		/* reload () {
			const _that = this;
			_that.isRouterAlive = false;
			_that.$nextTick(()=>{
				_that.isRouterAlive = true;
			});
		} */
	}
}
</script>

<style lang="scss" rel="stylesheet/scss">

</style>
