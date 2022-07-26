<script>
	import Alert from '../../components/secreto/Alert.svelte';
	import Header from '../../components/secreto/Header.svelte';
	import Message from '../../components/secreto/Message.svelte';
</script>

<svelte:head>
	<title>secreto &bull; @yuxxeun</title>
	<meta name="title" content="secreto &bull; @yuxxeun" />
	<meta name="description" content="send random message to me!" />
	<meta name="robots" content="noindex, nofollow" />
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="language" content="English" />
	<meta name="revisit-after" content="7 days" />
	<meta name="author" content="@yuxxeun" />
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://yuxxeun.vercel.app/" />
	<meta property="og:title" content="secreto &bull; @yuxxeun" />
	<meta property="og:description" content="send random message to me!" />
	<meta
		property="og:image"
		content="https://raw.githubusercontent.com/yuxxeun/yuxxeun/master/gradient.jpg"
	/>
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://yuxxeun.vercel.app/" />
	<meta property="twitter:title" content="secreto &bull; @yuxxeun" />
	<meta property="twitter:description" content="send random message to me!" />
	<meta
		property="twitter:image"
		content="https://raw.githubusercontent.com/yuxxeun/yuxxeun/master/gradient.jpg"
	/>
</svelte:head>

<section class="mx-auto px-10 w-5/6 my-10">
	<Header />
	<Alert />
	<Message />
</section>
