<template>
	<NavBar />
	<Hero />
	<Services />
	<Features />
	<Cta />
	<Footer />
</template>

<script lang="ts">
	import { RouterLink, RouterView } from 'vue-router';
	import { defineComponent } from 'vue';
	import NavBar from '@/components/Navbar.vue';
	import Footer from '@/components/Footer.vue';
	import Hero from '@/components/Hero.vue';
	import Services from '@/components/Services.vue';
	import Cta from '@/components/Cta.vue';

	import Features from '@/components/Features.vue';

	export default defineComponent({
		name: 'Home',
		components: {
			RouterLink,
			RouterView,
			NavBar,
			Hero,
			Services,
			Features,
			Cta,
			Footer,
		},
	});
</script>
