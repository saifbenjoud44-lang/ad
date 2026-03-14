<template>
  <div class="sidebar">
    <ul>
      <li><span class="icon modern">🏠</span><span class="text white">Admin Panel</span></li>
      <li><span class="icon modern">👋</span><span class="text white">Bienvenue</span></li>
      <li><span class="icon modern">🧑‍💼</span><span class="text white">nom</span></li>
      <li><span class="icon modern">👨‍🏫</span><span class="text white">Responsables</span></li>
      <li><span class="icon modern">👨‍🎓</span><span class="text white">Stagiaires</span></li>
      <li><span class="icon modern">⚙️</span><span class="text white">Paramètres</span></li>
      <li><span class="icon modern">🔙</span><span class="text white">Déconnexion</span></li>
      <li><span class="icon modern">📊</span><span class="text white">Tableau de Bord</span></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'AdminDashboard',
};
</script>

<style scoped>
.sidebar {
  background-color: #2ECC71; /* Keep the emerald color */
  padding: 20px;
}

.sidebar .text {
  color: white;
  font-weight: 600; /* Improve font weight */
  font-size: 16px; /* Better font size */
}

.icon {
  margin-right: 10px;
  /* Add modern styling for icons */
}

.modern {
  font-size: 20px; /* Enhance icon size */
}
</style>
