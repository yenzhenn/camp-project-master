<script setup>
import {ArrowRightIcon, ChevronDoubleDownIcon} from '@heroicons/vue/solid'
</script>
<template>
	<section class="bg-[url('/img/https://st.depositphotos.com/1028816/5159/v/450/depositphotos_51594437-stock-illustration-violoncello.jpg)]">
		<div class="flex flex-col w-full py-12 px-4 lg:px-0 justify-center items-end">
			<p class="text-2xl text-black font-medium">Hi！我是<span class="text-black">林言臻</span></p>
			<h1 class="text-5xl text-right text-black mt-1 font-extrabold">
				一個喜歡音樂的學生
			</h1>
			<p class="text-lg text-black font-light pt-8">
				[自我介紹]
			</p>
			<a
				href="#contact"
				class="mt-3 flex items-center text-black font-regular pb-2">
				聯絡我
				<ArrowRightIcon class="ml-1 w-5 h-5"/>
			</a>
		</div>

		<a href="#activities" class="animate-bounce cursor-pointer">
			<chevron-double-down-icon class="w-16 h-16"/>
		</a>
	</section>
</template>
