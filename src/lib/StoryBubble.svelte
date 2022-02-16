<script>
  import { createEventDispatcher } from 'svelte';

  let childs = [];

  function addChild() {
    alert("test");
  }
</script>


<div>
  <div class="overflow-visible relative max-w-sm mx-auto bg-white shadow-lg ring-1 ring-black/5 rounded-xl flex items-center gap-6 dark:bg-slate-800 dark:highlight-white/5">
    <div class="absolute -left-6 w-24 h-24 rounded-full shadow-lg">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-22 w-22 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
      </svg>
    </div>
    <div class="flex flex-col py-5 pl-24">
      <strong class="text-slate-900 text-sm font-medium dark:text-slate-200">Andrew Alfred</strong>
      <span class="text-slate-500 text-sm font-medium dark:text-slate-400">Technical advisor</span>
    </div>
    <button class="absolute -right-5 bottom-0 w-10 h-10 rounded-full shadow-lg" on:click={addChild}>
      <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z" />
      </svg>
    </button>
  </div>
</div>

