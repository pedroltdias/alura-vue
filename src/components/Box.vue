<template>
	<div class="box has-text-weight-bold" :style="estilos">
		<slot></slot>
	</div>
</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent({
	name: 'Box',
	data() {
		return {
			estilos: {
				background: '#FAF0CA'
				//'background-color': '#FAF0CA'
				//backgroundColor: '#FAF0CA'
			}
		}
	}
})

</script>