<script lang="ts">
	import { page } from '$app/stores';
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5 flex flex-col items-center">
		<h1 class="h1">{$page.status}</h1>
		<h3 class="h3">{$page.error?.message}</h3>
	</div>
</div>
