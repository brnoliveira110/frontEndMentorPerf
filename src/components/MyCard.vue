<script setup lang="ts">
</script>

<template>
  <div class="card">
    <div class="card-image">
      <img
        src="../assets/image-product-desktop.jpg"
        class="image"
        alt="Imagem de um perfume"
      />
    </div>
    <div class="card-descript">
      <p class="text-perfum">PERFUME</p>
      <h1
        class="
          text-2xl
          font-bold
          pb-4
          text-left
          font-sans
          max-[600px]:text-ms max-[600px]:pb-1
        "
      >
        Gabrielle Essence Eau De Parfum
      </h1>
      <p class="text-descrip">
        A floral, solar and voluptuous interpretation composed by Olivier Polge,
        Perfumer-Creator for the House of CHANEL.
      </p>
      <p
        class="
          text-value text-left
          pb-5
          text-emerald-600
          font-bold
          text-lg
          max-[600px]:text-ms
        "
      >
        $149.99
        <span class="line-through text-slate-400 text-xs pl-4">$169.99</span>
      </p>

      <button
        class="
          w-48
          bg-emerald-600
          text-white text-ls
          hover:bg-emerald-900 hover:border-transparent
          rounded
          text-base
          font-medium
          cursor-pointer
          p-2
          max-[600px]:text-xs
        "
      >
        Add to Cart
      </button>
    </div>
  </div>
</template>
<style scoped>
.card {
  @apply grid xl:grid-cols-2 sm:grid-cols-1 w-5/12 max-[600px]:w-60;
}

.card-image {
  @apply rounded-md max-[600px]:h-60;
}

.image {
  @apply rounded-l-md max-[1280px]:rounded-md;
}

.card-descript {
  @apply text-black
        p-8
        bg-white
        rounded-r-md
        max-[600px]:p-6 max-[600px]:rounded-none;
}

.text-perfum {
  @apply text-slate-400 text-sm
          pb-4
          text-left
          max-[600px]:text-xs max-[600px]:pb-1;
}

.text-descrip {
  @apply text-xs text-slate-400 text-left pb-4 max-[600px]:pb-2;
}
</style>
