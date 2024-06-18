<script lang="ts">
	import { MyCounterButton } from '@repo/ui';
	import { add, head } from '@repo/util';
	import { times } from '@repo/util/multiply';
</script>

{add(1)}
{times(1)}
{JSON.stringify(head([1, 2, 3, 4]), null, 2)}

<h1>Web</h1>
<MyCounterButton />
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
