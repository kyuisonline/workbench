<script lang="ts">
	import { Card } from '$lib';
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<section>
	<Card
		content={{
			heading: data.content.metadata.title,
			detail: `
				Hey there, I'm Kyu. I built this workbench to keep my project tools in one
				place. You may find the <a href="https://github.com/kyuisonline/workbench" class="underline"
					>repo</a
				> more interesting.
		`,
			isSkeletonCard: true
		}}
	/>
</section>
