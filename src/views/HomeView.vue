<script setup></script>

<template>
  <main>
    <div class="wrapper">
      <div class="header">
        <h4>written by Enrique on 6/10/2024</h4>
        <div class="actions">
          <span class="material-symbols-outlined"> delete </span>
          <span class="material-symbols-outlined"> edit </span>
        </div>
      </div>
      <div class="body">
        <h1>title</h1>
        <p>body</p>
      </div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.wrapper {
  width: 75%;
  background-color: red;
}
</style>
