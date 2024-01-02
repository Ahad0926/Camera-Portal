<script>
  import "../app.css";
  import Sidebar from "$lib/Sidebar.svelte";
  import Header from "$lib/Header.svelte";
</script>

<div class="flex">
  <Sidebar />
  <div class="flex-grow">
    <Header/>
    <slot />
  </div>
</div>
