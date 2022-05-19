<script setup>
import banner from "../assets/welcome.svg";

defineProps({
	msg: String,
});
</script>

<template>
	<section
		class="comming__section flex flex-col gap-5 justify-center items-center"
	>
		<img
			class="comming__soon__img"
			:src="banner"
			alt="JaydeepSuthar.tech"
		/>
		<h1
			class="comming__soon__text font-bold text-4xl lg:text-6xl hover:underline"
		>
			JaydeepSuthar.tech
		</h1>
		<p
			class="comming__soon__text font-bold text-2xl lg:text-4xl text-slate-500"
		>
			{{ msg }}
		</p>
	</section>
</template>
