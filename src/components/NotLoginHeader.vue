<template>
  <div>
    <header>
      <div class="logo-container">
        <nav class="gyraph-logo" @click="hoge">
          <router-link to="/">Gyraph</router-link>
        </nav>
        <div class="loginAndNewAccount">
          <button class="login">
            <router-link to="/login">ログイン</router-link>
          </button>
          <button class="new-account">
            新規登録
          </button>
        </div>
      </div>
    </header>
  </div>
</template>

<script lang="ts">
export default {
  name: 'NotLoginHeader',
  methods: {
    hoge() {
      console.log("hoge");
    }
  }
}
</script>
