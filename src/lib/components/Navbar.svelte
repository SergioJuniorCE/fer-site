<script lang="ts">
	const items: string[] = ['Rutinas', 'Nutrición', 'Entrenamiento', 'Precio', 'Contacto'];
</script>

<nav class="container flex items-center py-4 mt-4 sm:mt-12">
	<div class="py-1"><img src="/imgs/logo-bookmark.svg" alt="logo-bookmark.svg" /></div>
	<ul
		class="hidden sm:flex flex-1 justify-end items-center gap-12 text-company-purple uppercase text-xs px-2"
	>
		{#each items as item}
			<li class="cursor-pointer">{item}</li>
		{/each}
		<button type="button" class="bg-blue-800 text-white rounded-md px-7 py-3 uppercase"
			>Login</button
		>
	</ul>
	<div class="flex sm:hidden flex-1 justify-end">
		<i class="text-2xl fas fa-bars" />
	</div>
</nav>
