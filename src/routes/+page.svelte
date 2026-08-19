<script lang="ts">
  // Fantasy Novel Cover Landing Page
</script>

<div class="min-h-screen bg-[#050508] text-amber-50 flex flex-col items-center justify-center p-6 relative overflow-hidden font-serif selection:bg-amber-500 selection:text-black">
  {/* Background Glows */}
  <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-amber-950/20 via-slate-950/90 to-[#050508] pointer-events-none" />
  
  <div class="max-w-md w-full bg-slate-900/60 backdrop-blur-2xl border border-amber-500/30 p-8 sm:p-10 rounded-[3rem] shadow-[0_0_60px_rgba(0,0,0,0.9)] text-center space-y-8 relative z-10">
    
    {/* Magical Emblem */}
    <div class="w-20 h-20 bg-gradient-to-br from-amber-300 via-amber-500 to-amber-700 text-slate-950 font-black text-3xl rounded-3xl mx-auto flex items-center justify-center shadow-[0_0_30px_rgba(245,158,11,0.5)] border border-amber-200/50">
      📖
    </div>

    {/* Typography */}
    <div class="space-y-3">
      <span class="px-4 py-1.5 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-300 text-[10px] tracking-[0.3em] uppercase font-sans font-extrabold">
        The Chronicle of Ruins
      </span>
      <h1 class="text-4xl font-extrabold tracking-widest text-transparent bg-clip-text bg-gradient-to-b from-amber-100 via-amber-300 to-amber-600">
        RUINS
      </h1>
      <p class="text-xs text-amber-200/70 italic leading-relaxed px-2 font-serif">
        "Di balik reruntuhan dunia yang fana, takdir dan kekayaan ditempa dalam keabadian lembaran kode."
      </p>
    </div>

    {/* Divider */}
    <div class="flex items-center justify-center gap-3 opacity-50">
      <div class="h-[1px] w-12 bg-gradient-to-r from-transparent to-amber-500" />
      <span class="text-amber-400 text-xs">✦ ✧ ✦</span>
      <div class="h-[1px] w-12 bg-gradient-to-l from-transparent to-amber-500" />
    </div>

    {/* Buttons */}
    <div class="grid grid-cols-2 gap-3 pt-2 font-sans">
      <a 
        href="/login" 
        class="w-full bg-slate-800 hover:bg-slate-700 text-amber-200 border border-amber-500/40 py-4 rounded-2xl font-bold text-xs shadow-lg transition-all active:scale-95 flex items-center justify-center tracking-wider uppercase"
      >
        Masuk Gerbang
      </a>
      <a 
        href="/register" 
        class="w-full bg-gradient-to-r from-amber-500 to-amber-600 hover:from-amber-400 hover:to-amber-500 text-slate-950 py-4 rounded-2xl font-bold text-xs shadow-[0_0_20px_rgba(245,158,11,0.4)] transition-all active:scale-95 flex items-center justify-center tracking-wider uppercase"
      >
        Mulai Berpetualang
      </a>
    </div>

    <p class="text-[9px] text-amber-500/40 font-sans tracking-widest uppercase">
      MongoDB Atlas • SvelteKit Arcana
    </p>
  </div>
</div>
