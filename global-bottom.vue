<template>
  <footer
    v-if="![8, $slidev.nav.total].includes($slidev.nav.currentPage)"
    class="common-footer"
  >
    <span>
      Agentic AI Melbourne ·
      3 December 2026 ·
      <a href="https://aimelb.org">aimelb.org</a>
    </span>
    <span class="footer-meta">
      {{ $slidev.nav.currentPage }} of {{ $slidev.nav.total }}
    </span>
  </footer>
</template>
