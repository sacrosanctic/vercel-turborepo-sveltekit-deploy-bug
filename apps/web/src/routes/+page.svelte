<script lang="ts">
	import { MyCounterButton } from '@repo/ui';
	import { add } from '@repo/util';
	import { times } from '@repo/util/multiply';
</script>

{add(1)}
{times(1)}

<h1>Web</h1>
<MyCounterButton />
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
