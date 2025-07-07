<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
	import UseCases from "$lib/components/layout/UseCases.svelte";
</script>

<Hero
	title="Understand faster. Write better."
	subtitle="All your research, in one place."
	imageSrc="/generated/image-a-diverse-group-of-researchers-engaged-i.webp"
	centered={true}
/>
<LogoScroller 
	label="Trusted by leading research institutions"
	logoUrls={[
		'https://logo.clearbit.com/caltech.edu',
		'https://logo.clearbit.com/stanford.edu',
		'https://logo.clearbit.com/gsk.com',
		'https://logo.clearbit.com/biogen.com'
	]}
/>

<Summary
	title="What we do"
	text="Anara is an AI-powered platform that helps researchers quickly understand papers, books, and audio content. We streamline the entire research workflow by helping you organize findings and write well-cited documents."
/>

<Testimonials
	testimonials={[
		{
			name: "Astrid Vanmeer",
			position: "PhD Student",
			company: "Behavioral Neuroscience",
			quote:
				"Anara cut my literature review time from 6 weeks to 4 days. I can now read through 50 papers and extract key findings in hours, not weeks. This saved me an entire semester of research time.",
			image:
				"/generated/image-a-female-phd-student-researcher-is-deepl.webp"
		},
		{
			name: "Caspian Thorpe",
			position: "Medical Researcher",
			company: "Clinical Trials Division",
			quote:
				"Anara's referenced responses prevented citation errors that could have cost us our $2.3M grant. The platform's accuracy verification saved our research credibility and prevented potential publication retractions.",
			image:
				"/generated/image-a-male-medical-researcher-dressed-in-a-p.webp"
		},
		{
			name: "Indira Castellanos",
			position: "Research Team Lead",
			company: "Corporate Innovation",
			quote:
				"We eliminated $85K in external research consultant fees by using Anara. Our team now handles complex literature reviews internally, and collaborative features reduced project timelines by 40%.",
			image:
				"/generated/image-a-female-corporate-research-team-leader-.webp"
		}
	]}
/>

<Features
	title="Powerful features for researchers"
	subtitle="Everything you need to understand, organize, and write better research"
	features={[
		{
			title: "AI assistant for any content",
			description:
				"Upload PDFs, books, audio, and videos to get instant answers with referenced sources you can trust."
		},
		{
			title: "Always shows sources",
			description:
				"Every AI response includes citations and references, so you can verify accuracy and trace back to original content."
		},
		{
			title: "Multi-format support",
			description:
				"Works with PDFs, images, handwritten notes, audio recordings, YouTube videos, and over 90 languages."
		},
		{
			title: "Collaborative research",
			description:
				"Share documents, chat conversations, and work together in real-time with your research team."
		},
		{
			title: "AI-powered writing",
			description:
				"Get help with citations, autocomplete sentences, and improve your writing with AI editing tools."
		},
		{
			title: "Enterprise ready",
			description:
				"HIPAA compliant with single sign-on, advanced admin controls, and priority support for organizations."
		}
	]}
/>

<UseCases
	title="Use Cases"
	subtitle="Real-world applications for research professionals"
	useCases={[
		{
			title: "Accelerate academic research",
			description: "PhD students and academics can reduce literature review time from weeks to days. Upload papers, get instant insights, and maintain perfect citation accuracy throughout your research process.",
			image: "/generated/image-a-group-of-phd-students-gathered-around-.webp",
			link: {
				href: "/use-cases/academic-research",
				label: "Learn more"
			}
		},
		{
			title: "Streamline medical research",
			description: "Medical professionals can analyze clinical papers efficiently while ensuring citation accuracy. Prevent costly publication errors and maintain research credibility with referenced AI responses.",
			image: "/generated/image-a-team-of-medical-researchers-in-a-brigh.webp",
			link: {
				href: "/use-cases/medical-research",
				label: "Learn more"
			}
		},
		{
			title: "Enhance corporate research",
			description: "Replace expensive external research consultants with collaborative AI-powered tools. Teams can handle complex literature reviews internally and reduce project timelines by 40%.",
			image: "/generated/image-a-corporate-research-team-seated-in-a-mo.webp",
			link: {
				href: "/use-cases/corporate-research",
				label: "Learn more"
			}
		}
	]}
/>

<AboutTeaser />
<CallToAction />
