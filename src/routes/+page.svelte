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
	title="Consistent day trading profits from Japanese stocks"
	subtitle="Systematic algorithmic strategies that deliver results without coding skills. Risk only 10% while maintaining your core portfolio."
	imageSrc="/generated/image-a-confident-japanese-professional-sits-a.webp"
	centered={true}
/>
<LogoScroller
	label="Trusted by traders worldwide"
	logoUrls={[
		'https://cdn.brandfetch.io/robinhood.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/interactivebrokers.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/alpaca.markets/w/400/h/400/logo',
		'https://cdn.brandfetch.io/tradestation.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Takeshi Yamamoto",
			position: "Retail Day Trader",
			company: "10-Year Veteran",
			quote:
				"Kabugorithm reduced my screen time by 4 hours daily while maintaining consistent returns. The systematic approach removed emotional decision-making that cost me ¥8M last year.",
			image: "/generated/image-a-professional-japanese-businessman-stan.webp"
		},
		{
			name: "Haruka Tanaka",
			position: "Individual Investor",
			company: "¥150M Portfolio",
			quote:
				"I allocate just 10% to algorithmic trading and it generates 15% monthly returns with controlled risk. Finally, a proven system that doesn't require coding expertise or constant monitoring.",
			image: "/generated/image-a-professional-japanese-woman-seated-at-.webp"
		},
		{
			name: "Kenji Watanabe",
			position: "Former Salaryman Trader",
			company: "¥200M Achieved",
			quote:
				"The backtested strategies gave me confidence to transition from US equities to Japanese stocks. My average daily profit increased by ¥320K while risk decreased by 40%.",
			image: "/generated/image-a-professional-japanese-man-in-business-.webp"
		}
	]}
/>

<Features
	title="Why traders choose Kabugorithm"
	subtitle="Systematic strategies designed for Japanese retail investors who want algorithmic edge without complexity"
	features={[
		{
			title: "No coding required",
			description:
				"Build and deploy algorithmic strategies through intuitive visual tools. Focus on trading logic while our platform handles technical implementation."
		},
		{
			title: "Proven systematic approach",
			description:
				"Access pre-built strategies backed by rigorous backtesting and real-world performance. Learn from a founder who reached ¥100M through disciplined execution."
		},
		{
			title: "Risk-controlled allocation",
			description:
				"Trade with confidence using our 10% portfolio allocation framework. Pursue day trading profits while preserving your core long-term holdings."
		},
		{
			title: "Japanese market expertise",
			description:
				"Purpose-built for Japanese individual stocks with market-specific insights. Navigate Tokyo trading hours and local market dynamics with precision."
		},
		{
			title: "Comprehensive backtesting",
			description:
				"Validate every strategy against historical data before risking capital. Our infrastructure eliminates guesswork and builds trading confidence."
		},
		{
			title: "Reliable execution",
			description:
				"Execute trades at institutional speed during critical market moments. Never miss opportunities due to technical limitations or manual delays."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
