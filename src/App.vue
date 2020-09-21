<template>
  <div id="app">
    <div class="flex">
      <div class="w-1/2 bg-gray-600 min-h-screen relative">
        <div class="grid grid-cols-1 mt-6">
          <div class="mt-5">
            <SearchForm class="float-right mt-5 mr-5" />
          </div>
          <div>
            <StickerForm />
          </div>
        </div>

      </div>
      <div class="w-1/2 bg-gray-300 h-screen">
        <div class="flex h-screen">
          <div class="m-auto">
            <StickerPreview />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import SearchForm from "./components/SearchForm";
import StickerForm from "./components/StickerForm";
import StickerPreview from "./components/StickerPreview";

export default {
  name: 'App',
  components: {
    SearchForm,
    StickerForm,
    StickerPreview
  }
}
</script>

<style>

</style>