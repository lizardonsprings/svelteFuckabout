<script lang="ts">
	import Logo from '$lib/components/logo.svelte';
</script>

<svelte:head>
	<title>SKELETON</title>
	<meta
		name="description"
		content="Sveltekit Auth Starter - An open source auth starter project utilizing lucia-auth, skeleton ui, prisma and sveltekit."
	/>
</svelte:head>
<div class="flex flex-col justify-center px-6 py-12 lg:px-8 mx-auto max-w-2xl">
	<div class="card p-6 pb-8 pt-8">
		<div>
			<div class="flex flex-row justify-center items-center mb-4">
				<div>
					<Logo size="42" />
				</div>
			</div>
			<div class="flex flex-row justify-center items-center mb-4">
				<h2>OH HI MY NAMES TERRY AND I SHAT IN MY FUCKIN TROUSERS</h2>
			</div>

			<hr class="!border-t-2 mt-2 mb-6" />
			<p>
				This is a sveltekit auth starter. It is an <a
					href="https://github.com/delay/sveltekit-auth-starter">open source auth starter project</a
				>
				utilizing
				<a href="https://lucia-auth.com/">Lucia</a> for authentication,
				<a href="https://www.skeleton.dev/">Skeleton</a> for ui elements,
				<a href="https://www.prisma.io/">Prisma</a>
				for database connectivity and type safety, <a href="https://lucide.dev/">Lucide</a> for
				icons, <a href="https://inlang.com/">Inlang</a> for internationalization and
				<a href="https://kit.svelte.dev/">Sveltekit</a> for the javascript framework. It has email verification,
				password reset, and will send an email out if the user changes their email address to re-verify
				it. It is released as open source under an MIT license.
			</p>
		</div>
	</div>
</div>

<style>
</style>
