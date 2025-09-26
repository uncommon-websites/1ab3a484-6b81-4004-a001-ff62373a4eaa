<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="More money from your content."
	subtitle="One platform to grow, sell, and partner."
	imageSrc="/generated/image-a-group-of-confident-young-adults-captur.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by leading creators and brands"
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/glossier.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/gymshark.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/warbyparker.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Built for TikTok creators"
	subtitle="Everything you need to maximize your TikTok Shop earnings in one unified platform"
	features={[
		{
			title: "TikTok Shop revenue optimization",
			description:
				"AI-powered analytics identify your highest-converting content and optimal posting times, turning missed opportunities into consistent revenue growth.",
			imageSrc: "/generated/image-a-tiktok-creator-sits-at-a-cozy-coffee-s.webp"
		},
		{
			title: "Unified brand partnership hub",
			description:
				"Connect with premium brands seamlessly through our creator-first ecosystem, eliminating the fragmentation that limits your earning potential.",
			imageSrc: "/generated/image-a-diverse-group-of-creators-and-brand-ma.webp"
		},
		{
			title: "Creator growth analytics",
			description:
				"Deep TikTok Shop insights show exactly how to scale your presence and earnings with data-driven recommendations tailored to your niche.",
			imageSrc: "/generated/image-a-young-creator-celebrating-personal-ach.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
