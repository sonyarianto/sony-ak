<script lang="ts">
	import { dev } from '$app/environment';
</script>

<svelte:head>
	<title>Sony AK</title>
	<meta
		name="description"
		content="Sony AK is a full-stack engineer living in Jakarta, Indonesia."
	/>
	{#if !dev}
		<!-- Global site tag (gtag.js) - Google Analytics -->
		<script async src="https://www.googletagmanager.com/gtag/js?id=G-YCW4JPDBJM"></script>
		<script>
			window.dataLayer = window.dataLayer || [];
			function gtag() {
				dataLayer.push(arguments);
			}
			gtag('js', new Date());

			gtag('config', 'G-YCW4JPDBJM');
		</script>
	{/if}
</svelte:head>

<div id="page-wrapper">
	<div id="header-wrapper" />

	<div id="banner-wrapper">
		<div id="banner" class="box container">
			<div class="row">
				<div class="col-7 col-12-medium">
					<header id="header" class="container">
						<div id="logo">
							<img
								style="width:120px;height:120px;border:5px solid #cecece;border-radius:100px;display:block;object-fit:cover;"
								src="https://polywork-production.imgix.net/kj28ennqhvju4vlc55mxe4eh3vmc?ixlib=rails-4.2.0&fit=crop&auto=format&q=100"
								alt="Sony AK"
							/>
						</div>
					</header>
					<h2>Hi. I'm Sony AK.</h2>
					<p>Principal Full-Stack Engineer</p>
				</div>
				<div class="col-5 col-12-medium">
					<ul>
						<li>
							<a
								target="_blank"
								rel="noreferrer"
								href="https://github.com/sonyarianto"
								class="button large icon brands fa-github">GitHub</a
							>
						</li>
						<!-- <li>
							<a href="mailto:sony@sony-ak.com" class="button large icon solid fa-at">E-mail</a>
						</li> -->
						<li>
							<a
								target="_blank"
								rel="noreferrer"
								href="https://www.google.com/search?q=what+is+full+stack+engineer"
								class="button large icon solid fa-cubes">Full-Stack?</a
							>
						</li>
                        <li>
							<a
								target="_blank"
								rel="noreferrer"
								href="https://youtube.com/@bljdev"
								class="button large icon brands fa-youtube">BLJ</a
							>
						</li>
                        <li>
							<a
								target="_blank"
								rel="noreferrer"
								href="https://youtube.com/@adayangtanya"
								class="button large icon brands fa-youtube">ada yang tanya</a
							>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>

	<div id="footer-wrapper">
		<footer id="footer" class="container">
			<div class="row">
				<div class="col-12">
					<div id="copyright">
						<ul class="menu">
							<li>&copy; 2003-{new Date().getFullYear()} Sony AK</li>
							<li>Made with <span style="color:red;">&#10084;</span> in Jakarta</li>
							<li>
								Design based on <a
									target="_blank"
									rel="noreferrer"
									href="https://html5up.net/uploads/demos/verti">Verti</a
								>
							</li>
							<li>
								Crafted using <a target="_blank" rel="noreferrer" href="https://kit.svelte.dev"
									>SvelteKit</a
								>
							</li>
							<li>
								Hosted at <a target="_blank" rel="noreferrer" href="https://vercel.com">Vercel</a>
							</li>
							<li>
								DNS by <a target="_blank" rel="noreferrer" href="https://cloudflare.com"
									>Cloudflare</a
								>
							</li>
							<li>
								Repository by <a target="_blank" rel="noreferrer" href="https://github.com"
									>GitHub</a
								>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</footer>
	</div>
</div>
