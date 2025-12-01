<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <section class="home-container">
    <div class="hero">
      <h1 class="title">Slumbr — Sleep Tracker</h1>
      <p class="subtitle">
        Acompanha o teu sono. Melhora hábitos. Sobe de nível.
      </p>
      <router-link to="/sleep" class="btn-primary">
        Começar
      </router-link>
    </div>

    <div class="features">
      <div class="card">
        <h3>Regista o teu sono</h3>
        <p>Anota as horas dormidas todos os dias.</p>
      </div>

      <div class="card">
        <h3>Estatísticas</h3>
        <p>Descobre padrões de sono através de gráficos.</p>
      </div>

      <div class="card">
        <h3>Gamificação</h3>
        <p>Ganha XP, sobe de nível e desbloqueia badges.</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.home-container {
  padding: 40px;
  text-align: center;
}

.hero {
  margin-bottom: 50px;
}

.title {
  font-size: 3rem;
  margin-bottom: 10px;
  font-weight: bold;
}

.subtitle {
  font-size: 1.2rem;
  opacity: 0.7;
  margin-bottom: 30px;
}

.btn-primary {
  display: inline-block;
  background: #4f46e5;
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.2s ease;
}

.btn-primary:hover {
  background: #4338ca;
}

.features {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.card {
  width: 260px;
  padding: 20px;
  border-radius: 12px;
  background: #fafafa;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
</style>

