<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style lang="scss">
	/*每个页面公共css */
	@import './css/iconfont.css';
	button {
		padding: 0;
		margin: 0;
	}
	button::after {
		border: 0;
		border-radius: 0;
	}
</style>
