auto_awesome
原文語言： 英文
489 / 5000
翻譯結果
<template>
	<div class="col-xs-offset-2 col-xs-8">
		<div class="page-header">
			<h2>Vue Router Demo</h2>
			<button @click="back">後退</button>
			<button @click="forward">前進</button>
			<button @click="test">測試一下go</button>
		</div>
	</div>
</template>

<script>
	export default {
		name:'Banner',
		methods: {
			back(){
				this.$router.back()
				// console.log(this.$router)
			},
			forward(){
				this.$router.forward()
			},
			test(){
				this.$router.go(3)
			}
		},
	}
</script> 