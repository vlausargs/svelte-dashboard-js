<script>
	import '../app.css';

	export let data;
</script>

<div class="flex flex-col w-[calc(100vw)] min-h-[calc(100vh)] h-full">
	<div class="flex flex-row w-full">
		<div class="flex flex-row flex-1 space-x-3">
			<div class="flex col pr-20">Icon</div>
			<div class="flex col">Home</div>
			<div class="flex col">Dashboard</div>
			<div class="flex col">Sales</div>
		</div>
		<div class="flex flex-row pr-10">right side</div>
	</div>
	<div class="flex flex-col w-full h-full">
		<!-- content -->
		<slot />
	</div>
</div>
