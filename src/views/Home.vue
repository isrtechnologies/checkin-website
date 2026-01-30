<script setup lang="ts">
// No script needed for now
</script>

<template>
  <div>
    <header>
      <h1>Are You Alive</h1>
      <img src="/screenshots/AreYouAlive.png" alt="Are You Alive App Screenshot" class="main-image" />
    </header>
    <main>
      <section class="description">
        <h2>About the App</h2>
        <p>Are You Alive is a mobile app designed to help you stay connected with your loved ones. Check in regularly to let them know you're safe and sound.</p>
      </section>
      <!-- <section class="screenshots">
        <h2>Screenshots</h2>
        <div class="screenshot-grid">
          <img src="/screenshots/AreYouAlive.png" alt="Screenshot 1" />
        </div>
      </section> -->
    </main>
  </div>
</template>

<style scoped>
header {
  text-align: center;
  margin-bottom: 40px;
}

.main-image {
  max-width: 300px;
  height: auto;
  margin: 20px 0;
}

.description {
  margin-bottom: 40px;
}

.screenshots {
  margin-bottom: 40px;
}

.screenshot-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.screenshot-grid img {
  width: 100%;
  height: auto;
  border-radius: 8px;
}
</style>