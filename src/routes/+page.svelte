<script>
	import {
		AboutMeSection,
		HeroSection,
		MyWorkSection,
		SkillsSection,
		ContactSection
	} from '$components';

	const { data } = $props();
	let { workExperience, projects, skills } = data;
	$inspect(skills);
</script>

<HeroSection />
<AboutMeSection {workExperience} />
<MyWorkSection {projects} />
<SkillsSection {skills} />
<ContactSection />
