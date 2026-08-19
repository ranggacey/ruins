<script>
  import '../app.css';
  let { children } = $props();
</script>

<div class="min-h-screen bg-[#050508] text-amber-50 font-serif antialiased">
  {@render children()}
</div>
