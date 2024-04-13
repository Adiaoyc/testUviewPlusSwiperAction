<template>
	<view>


		<up-swipe-action :autoClose="true">
			<up-swipe-action-item :options="options1">
				<view style="height: 100px; background-color: aqua;">
					111111111
				</view>
			</up-swipe-action-item>
			<up-swipe-action-item :options="options1">
				<view style="height: 100px; background-color: aqua;">
					111111111
				</view>
			</up-swipe-action-item>

		</up-swipe-action>

	</view>
</template>

<script setup>
	import {
		ref,
		reactive
	} from "vue";
	
	let options1 = reactive([{
		text: '删除',
		style: {
			backgroundColor: '#dd524d'
		}
	}]);
</script>

<style lang="scss" scoped>

</style>