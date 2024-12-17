<template>
  <div class="login">
    <h2>Login</h2>
    <form @submit.prevent="login">
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" v-model="email" class="form-control" placeholder="Enter email" />
      </div>
    </form>
  </div>
</template>
<script lang="ts"></script>
