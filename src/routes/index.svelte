<script>
	import TestComponent from "../components/TestComponent.svelte";
</script>

<style>
	.centerer {
		@apply flex-1 flex flex-col items-center justify-center;
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<div class="flex flex-col w-full min-h-screen leading-none">
	<div class="flex flex-col flex-1" id="sapper">
		<div class:centerer={true}>
			<!-- Here's how you could extract conditional class groups with @apply -->
			<TestComponent title="🌐 Sapper with PostCSS project base"
				paragraph="This is an example route and component to make sure everything's working." />
		</div>
	</div>
</div>