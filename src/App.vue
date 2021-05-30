<template>
  <div class id="app">
    <div class="container grid-lg">
      <header class="navbar">
        <section class="navbar-section">
          <router-link to="/" class="btn btn-link">Home</router-link>
          <router-link to="/kanban" class="btn btn-link">Kanban</router-link>
        </section>
        <section class="navbar-center">
          <img
            class="img-responsive img-logo"
            src="@/assets/logo.png"
            alt="Logo da Switch Case"
          />
        </section>
        <section class="navbar-section">
          <a href="https://www.twitter.com" class="btn btn-link" target="_blank"
            >Twitter</a
          >
          <a
            href="https://www.instagram.com"
            class="btn btn-link"
            target="_blank"
            >Instagram</a
          >
        </section>
      </header>
      <router-view class="pt-2" />
    </div>
  </div>
</template>

<style scoped>
.img-logo {
  margin-top: 80px;
  margin-bottom: 20px;
  max-width: 100px;
}
</style>