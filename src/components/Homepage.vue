<template>
	<div class="containerFull">
		<button class="btn">{{dataName}}</button>

		<example-component></example-component>
	</div>
</template>

<script>
	import { EventBus } from './Parts/EventBus';
	import exampleComponent from './Parts/exampleComponent';

	export default {
		components: {
			'example-component': exampleComponent
		},
		name: 'Homepage',
		mounted() {
			
		},
		data () {
			return {
				logging: false,
				dataName: 'Turtles'
			}
		},
		methods: {
			
		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="./../assets/scss/base.scss" lang="scss">

</style>
