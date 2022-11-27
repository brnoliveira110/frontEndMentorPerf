<script setup lang="ts">
</script>

<template>
  <div class="grid xl:grid-cols-2 sm:grid-cols-1 w-5/12 max-[600px]:w-60">
    <div class="rounded-md max-h-80">
      <img
        src="../assets/image-product-desktop.jpg"
        class="rounded-l-md max-[1280px]:rounded-md"
        alt="Imagem de um perfume"
      />
    </div>
    <div class="text-black p-8 bg-white rounded-md max-h-96">
      <p class="text-slate-400 text-sm pb-4 text-left">PERFUME</p>
      <h1 class="text-2xl font-bold pb-4 text-left font-sans">
        Gabrielle Essence Eau De Parfum
      </h1>
      <p class="text-xs text-slate-400 text-left pb-4">
        A floral, solar and voluptuous interpretation composed by Olivier Polge,
        Perfumer-Creator for the House of CHANEL.
      </p>
      <p class="text-left pb-4 text-emerald-600 font-bold text-lg">
        $149.99
        <span class="line-through text-slate-400 text-xs pl-4">$169.99</span>
      </p>

      <button
        class="
          w-48
          bg-emerald-600
          text-white text-ls
          hover:bg-emerald-900 hover:border-transparent
        "
      >
        Add to Cart
      </button>
    </div>
  </div>
</template>
