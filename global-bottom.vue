<!-- ページ用フッターの一例 -->
<template>
    <!-- $slidev.nav.currentPage !== 4 -->
    <footer
      v-if="$slidev.nav.currentLayout !== 'cover'"
      class="absolute bottom-0 left-0 right-0 text-gray-500 p-2 text-xs"
    >
    © 2024 LayerX Inc.
    </footer>
  </template>
