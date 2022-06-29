<script>
	import { appName, appDescription } from '../config/config';
	import { Section, Column } from '@mateoroldos/svelte.bones';
</script>

<Section>
	<Column justify="center">
		<h1>Welcome to {appName}</h1>
		<p>{appDescription}</p>
	</Column>
</Section>
