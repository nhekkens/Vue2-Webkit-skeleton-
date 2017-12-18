<template>
	<p>{{importantMessage}}</p>
</template>

<script>
	import { EventBus } from './EventBus';

	export default {
		name: 'exampleComponent',
		mounted() {
			
		},
		data () {
			return {
				logging: false,
				importantMessage: 'I like turtles'
			}
		},
		methods: {
			
		}
	}
</script>
