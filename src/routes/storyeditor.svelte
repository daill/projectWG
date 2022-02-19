<script>
	import StoryBubble from '$lib/StoryBubble.svelte';

	function addChild() {

	}
</script>

<svelte:head>
	<title>editor</title>
</svelte:head>

<section>
	<h1>
    <div class="rounded-lg border-emerald-300 border-solid">
      test entry
		</div>
	</h1>

  <div class="grid grid-cols-3 gap-4">
    <div>
      <StoryBubble />
    </div>
  </div>
</section>
