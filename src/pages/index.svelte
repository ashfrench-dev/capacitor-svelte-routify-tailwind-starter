<script>
  import { goto } from "@roxi/routify";
</script>

<div class="h-32">
  hello world! <span class="text-blue-700" on:click={$goto("/new")}>click me!</span> to make sure routes are working
</div>
