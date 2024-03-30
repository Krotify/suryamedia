<script>
  import Product from "./product.svelte";
</script>

<div class="grid grid-cols-5">
  <div></div>
  <div class="col-span-2">
    <h1 class="ml-6 text-4xl font-extrabold">Semua Produk</h1>
  </div>
</div>

<div class="m-12 grid grid-cols-5 gap-8">
  <div class="left-side h-fit max-w-full rounded-xl bg-[#F2F2F2] p-6">
    <h1 class="header1">Kategori</h1>
    <ul class="space-y-2">
      {#each { length: 5 } as _, i}
        <li>
          <div class="m-2 flex items-center">
            <input
              id="checkbox"
              type="checkbox"
              value=""
              class="h-4 w-4 rounded border-black bg-[#F2F2F2] text-blue-600 focus:ring-2 focus:ring-blue-500"
            />
            <label for="checkbox" class="ms-2 text-sm font-medium"
              >Keramik Anu</label
            >
          </div>
        </li>
      {/each}
    </ul>
    <div class="my-4 space-y-2 border-y border-gray-600 py-4">
      <h1 class="header1">Harga</h1>
      <!-- future slider implementation https://medium.com/@predragdavidovic10/native-dual-range-slider-html-css-javascript-91e778134816 -->
      <div class="flex justify-between">
        <label
          for="default-range"
          class="mb-2 block text-sm font-medium text-black">0k</label
        >
        <label
          for="default-range"
          class="mb-2 block text-sm font-medium text-black">125k</label
        >
      </div>
      <input
        id="default-range"
        type="range"
        value="50"
        class="h-2 w-full cursor-pointer appearance-none rounded-lg bg-[#FBA000]"
      />
    </div>
    <div class="my-4">
      <h1 class="header1">Warna</h1>
      <ul class="space-y-2">
        {#each { length: 5 } as _, i}
          <li>
            <div class="m-2 flex items-center">
              <input
                id="checkbox"
                type="checkbox"
                value=""
                class="h-4 w-4 rounded border-black bg-[#F2F2F2] text-blue-600 focus:ring-2 focus:ring-blue-500"
              />
              <label for="checkbox" class="ms-2 text-sm font-medium"
                >Keramik Anu</label
              >
            </div>
          </li>
        {/each}
      </ul>
    </div>
  </div>
  <div class="right-side col-span-4">
    <h1 class="header1 rounded-lg bg-[#F2F2F2] px-4 py-2 text-2xl">Sort By</h1>
    <div class="mx-2 my-8 grid gap-8 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 2xl:grid-cols-5">
      <!-- product component -->
      {#each { length: 20 } as _, i}
        <Product />
      {/each}
    </div>
  </div>
</div>

<style>
  .header1 {
    font: bold;
    font-weight: 700;
    margin: 0.5rem;
  }
</style>
