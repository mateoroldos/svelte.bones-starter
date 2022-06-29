<script>
	import { appName, appDescription } from '../config/config';
	import Section from '$lib/components-delete/Section.svelte';
	import Column from '$lib/components-delete/Column.svelte';
</script>

<Section>
	<Column justify="center">
		<h1>Welcome to {appName}</h1>
		<p>{appDescription}</p>
	</Column>
</Section>
