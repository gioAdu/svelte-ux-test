<script>
	import '../app.pcss';
	import { ThemeSwitch, Settings } from 'svelte-ux';
</script>

<Settings>
	<slot />

	<ThemeSwitch />
</Settings>
