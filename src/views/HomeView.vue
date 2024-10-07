<script setup></script>

<template>
  <main>
    <div class="wrapper">
      <div class="header">
        <h4>written by Enrique on 6/10/2024</h4>
        <div class="actions">
          <span class="material-symbols-outlined action-icon red"> delete </span>
          <span class="material-symbols-outlined action-icon green"> bookmark </span>
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
.red {
  color: red;
}

.green {
  color: green;
}

.header {
  display: flex;
  border-radius: 0.5rem 0.5rem 0 0;
  justify-content: space-between;
  align-items: center;
  background-color: blue;
  padding: 1rem;
}
.wrapper {
  border-radius: 0.5rem;
  width: 75%;
  background-color: red;
}
.body {
  padding: 1rem;
}
.action-icon {
  background-color: white;
  padding: 0.5rem;
  border-radius: 50%;
  margin: 0.5rem;
}
</style>
