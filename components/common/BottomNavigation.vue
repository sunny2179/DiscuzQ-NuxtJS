<template>
	<v-bottom-navigation grow app color="primary" class="hidden-lg-and-up bottom-navigation">
		<v-btn @click="$emit('start')">
			<span>发现</span>
			<v-icon>mdi-compass-outline</v-icon>
		</v-btn>
	</v-bottom-navigation>
</template>

<script>
export default {
	data() {
		return {};
	},
};
</script>

<style lang="less">
.bottom-navigation{
	z-index: 9 !important;
}
</style>