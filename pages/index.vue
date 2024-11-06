<script lang="ts" setup></script>

<template>
  <header>
    <ul class="list">
      <li>
        <NuxtLink to="/">前台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">前台 About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin">前往 後台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin/order">前往 後台訂單</NuxtLink>
      </li>
    </ul>
  </header>
  <h1>
    前台首頁
  </h1>

  <button
    type="button"
    class="btn btn-primary"
  >Primary</button>
  <button
    type="button"
    class="btn btn-secondary"
  >Secondary</button>
  <button
    type="button"
    class="btn btn-success"
  >Success</button>
  <button
    type="button"
    class="btn btn-danger"
  >Danger</button>
  <button
    type="button"
    class="btn btn-warning"
  >Warning</button>
  <button
    type="button"
    class="btn btn-info"
  >Info</button>
  <button
    type="button"
    class="btn btn-light"
  >Light</button>
  <button
    type="button"
    class="btn btn-dark"
  >Dark</button>
  <button
    type="button"
    class="btn btn-link"
  >Link</button>
  <footer>
    <h5>
      前台模板的表尾
    </h5>
  </footer>
</template>

<style scoped></style>