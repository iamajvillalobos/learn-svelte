<script>
	import TwitterCard from "./TwitterCard.svelte";
	const aj = {
		profilePhoto:
			"https://pbs.twimg.com/profile_images/1226171508101246976/DstEjaMx_400x400.jpg",
		coverPhoto:
			"https://pbs.twimg.com/profile_banners/1370903546/1605513363/600x200",
		name: "AJ Villalobos",
		handler: "@iamajvillalobos",
		bio: "Software Engineer | Ruby & Javascript | Founder of btfy.io",
		location: "Philippines",
		joinedDate: "June 2013",
		birthday: "April 11, 1991",
		followersCount: 236,
		followingCount: 488,
	};

	const mark = {
		profilePhoto:
			"https://pbs.twimg.com/profile_images/1286543108545499136/cWpgL1DK_400x400.png",
		coverPhoto:
			"https://pbs.twimg.com/profile_banners/1402596174/1552791379/1500x500",
		name: "Mark",
		handler: "@MarkFChavez",
		bio: "Software. Travel. Aways a student.",
		location: "Philippines",
		joinedDate: "May 2013",
		birthday: "---",
		followersCount: 112,
		followingCount: 0,
	};

	const tophs = {
		profilePhoto:
			"https://pbs.twimg.com/profile_images/747350998855778306/RPg0fpnq_400x400.jpg",
		coverPhoto:
			"https://pbs.twimg.com/profile_banners/1654810910/1467017283/1500x500",
		name: "Tophs Celestial",
		handler: "@tophscelestial",
		bio: "---",
		location: "Makati City",
		joinedDate: "August 2013",
		birthday: "---",
		followersCount: 14,
		followingCount: 40,
	};

	const billy = {
		profilePhoto:
			"https://pbs.twimg.com/profile_images/819701663799779328/-D82wy4t_400x400.jpg",
		coverPhoto:
			"https://pbs.twimg.com/profile_banners/3166824524/1430006361/1500x500",
		name: "Billy Nicart",
		handler: "@itsmebilly1201",
		bio: "Software Engineer. Optimist.",
		location: "---",
		joinedDate: "April 2015",
		birthday: "---",
		followersCount: 66,
		followingCount: 220,
	};
</script>

<div class="grid grid-cols-1 md:grid-cols-2">
	<TwitterCard {...aj} />
	<TwitterCard {...mark} />
	<TwitterCard {...tophs} />
	<TwitterCard {...billy} />
</div>
