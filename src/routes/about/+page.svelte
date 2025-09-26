<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Creator-first",
			description: "Every feature, every partnership, every decision starts with what creators actually need to succeed."
		},
		{
			title: "Revenue-focused",
			description: "We measure success by how much more our creators earn, not by vanity metrics or engagement rates."
		},
		{
			title: "Platform-native",
			description: "Built specifically for TikTok Shop—we understand the ecosystem and work within it, not against it."
		}
	];
</script>

<SecondaryHero
	title="Make creators the priority"
	subtitle="Built for the TikTok Shop economy"
	imageSrc="/generated/image-a-small-diverse-group-of-people-collabor.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"The creator economy isn't broken. It's just scattered. Waves Network started with a simple question: why are so many TikTok creators losing money, even with millions of views? Founder Bruce Weaver saw creators struggling to manage brand deals, platform logistics, and order fulfillment—juggling ten open tabs while still missing out on real earnings. It wasn't a lack of talent. It was a fragmented system built for everyone but the people actually creating value.",
		"So we built what creators truly needed. Waves Network was shaped by listening closely to TikTok Shop creators. We uncovered where the friction lived—disconnected brand communication, unclear pricing models, and limited access to shared insights. Step by step, we designed a unified platform that works the way creators do: fully aligned with TikTok Shop, creator-first by design, and focused on real revenue—not vanity metrics.",
		"Today, we help TikTok creators turn influence into income by connecting them with over 10,000 brand partnerships. Our mission is simple—make the creator economy easier, more profitable, and built around the people driving its growth. When creators win, everyone wins. And we're just getting started."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	generating
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	generating
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to maximize your creator income?"
	subtitle="Join thousands earning more with brand partnerships"
	description="Stop leaving money on the table. Get access to over 10,000 brand partnerships, streamlined TikTok Shop integration, and tools built specifically for creators who want to turn influence into real revenue."
	imageSrc="/generated/image-a-professional-tiktok-creator-smiling-co.webp"
/>
