<template>
	<div class="makeTealLight">
		<BuildingSection class="pageWrapper pageTopContent">
			<BuildingHeadersBigger class="titleMarge">
				<span>HackMD</span>
				<br/>
				<span>留言功能優化</span>
			</BuildingHeadersBigger>
			<img src="/images/HackMD-Comment-MainPic.png">
		</BuildingSection>
	</div>
</template>
<script lang="ts">
	import Vue from 'vue';

	import BuildingSection from '@/components/building/section.vue';
	import BuildingHeadersBigger from '@/components/building/headers/bigger.vue';

	export default Vue.extend({
		components: {
			BuildingSection,
			BuildingHeadersBigger,
		}
	})
</script>
<style scoped>
.pageTopContent > img {
	display: block;
	width: 100%;
	position: relative;
	object-position: center;
	object-fit: contain;
	margin: 0px auto;
	transform: translateY(45px);
	filter: drop-shadow(var(--shadow-picture));
}
</style>