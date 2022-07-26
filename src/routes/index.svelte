<script>
	import Profile from '../components/index/Profile.svelte';
	import Footer from '../components/index/Footer.svelte';
	import Link from '../components/index/Link.svelte';
</script>

<svelte:head>
	<title>@yuxxeun</title>
	<meta name="title" content="@yuxxeun" />
	<meta name="robots" content="noindex, nofollow" />
	<meta name="description" content="making cool shit cybernetically." />
	<meta name="robots" content="noindex, nofollow" />
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="language" content="English" />
	<meta name="revisit-after" content="7 days" />
	<meta name="author" content="@yuxxeun" />
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://yuxxeun.vercel.app/" />
	<meta property="og:title" content="@yuxxeun" />
	<meta property="og:description" content="making cool shit cybernetically." />
	<meta
		property="og:image"
		content="https://raw.githubusercontent.com/yuxxeun/yuxxeun/master/gradient.jpg"
	/>
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://yuxxeun.vercel.app/" />
	<meta property="twitter:title" content="@yuxxeun" />
	<meta property="twitter:description" content="making cool shit cybernetically." />
	<meta
		property="twitter:image"
		content="https://raw.githubusercontent.com/yuxxeun/yuxxeun/master/gradient.jpg"
	/>
</svelte:head>

<section class="text-center">
	<Profile />
	<Link />
	<Footer />
</section>
