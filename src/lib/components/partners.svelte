<script>
	import bosch from '$lib/img/bosch.svg';
	import deloitte from '$lib/img/deloitte.svg';
	import solanabeach from '$lib/img/solanabeach.svg';
	import superteamgermany from '$lib/img/superteamgermany.svg';
	import wmdatenservice from '$lib/img/wmdatenservice.svg';
	import Marquee from 'svelte-fast-marquee';
</script>

<div class="mx-auto mt-32 max-w-6xl px-3 sm:px-6">
	<h2 class="mb-1 text-center text-lg font-medium sm:text-xl md:text-2xl">Project Partners</h2>
	<p
		class="mx-auto mb-10 max-w-2xl text-center text-xs text-muted-foreground sm:text-sm md:text-base"
	>
		Blocksprint enables partners to attain high-quality solutions to their Web3-related problems.
	</p>
</div>
<div>
	<Marquee gap="70px" speed={30}>
		<img src={bosch} alt="Bosch" class="mx-auto h-8" />
		<img src={wmdatenservice} alt="WM Datenservice" class="mx-auto h-8" />
		<img src={deloitte} alt="Deloitte" class="mx-auto h-8" />
		<img src={solanabeach} alt="Solanabeach" class="mx-auto h-8" />
		<img src={superteamgermany} alt="Superteam Germany" class="mx-auto h-8" />
	</Marquee>
</div>
