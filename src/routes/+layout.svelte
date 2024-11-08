<script lang="ts">
  import "../app.css";
  let { children } = $props();
</script>

<div class="flex-1">
  <div class="container relative pb-10 pt-10">
    <div class="bg-background overflow-hidden rounded-[0.5rem] border shadow-xl">
      {@render children()}
    </div>
  </div>
</div>