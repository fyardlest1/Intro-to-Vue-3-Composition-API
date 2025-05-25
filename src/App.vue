<!-- first part is the setup -->
<script setup>
import { ref } from 'vue';
const product = ref('Boots');
const description = ref('Beautiful boots for the summer');
</script>

<!-- second part is the template -->
<template>
	<div class="product-display">
		<div class="product-container">
			<div class="product-info">
				<h1>{{ product }}</h1>
				<p>{{ description }}</p>
			</div>
		</div>
	</div>
</template>
