<script setup>
import {ArrowRightIcon} from "@heroicons/vue/outline";

const skills = [
	{
		title: '運動',
		description: '不太擅長，但是必須的(加油',
	},
	{
		title: '音樂',
		description: '學習不同領域的樂器，目前5種 ',
	},
	{
		title: '繪畫',
		description: '偶爾會畫插圖',
	},
	{
		title: '烹飪',
		description: '努力不煮出黑暗料理',
	},
	{
		title: '攝影',
		description: '期待有機會學習',
	},
  {
    title: '未來',
    description: '挖掘更多不一樣的可能',
},
]
</script>

<template>

	<section id="about" class="pt-32 md:px-16 bg-gray-800">
		<div class="flex flex-col md:flex-row justify-between items-center md:px-8 md:mb-4">
			<h1 class="text-2xl md:text-4xl text-white font-bold">
				關於我
			</h1>
			<button
				class="my-8 mr-3 border-b border-white pb-2 flex items-center text-xl text-white">
				所有經歷
				<ArrowRightIcon class="ml-1 w-5 h-5"/>
			</button>
		</div>
		<div class="flex flex-wrap justify-start">
			<div
				class="w-full md:w-1/3"
				v-for="skill in skills">
				>
				<div
					class="px-10 sm:px-20 py-3 sm:py-6 shadow-lg w-11/12 mx-auto bg-white rounded z-20 relative">
					<h4 class="text-gray-800 text-lg text-center mb-2">{{ skill.title }}</h4>
					<p class="text-gray-600 text-lg text-center mb-2">{{ skill.description }}</p>
				</div>
			</div>
		</div>
	</section>
</template>