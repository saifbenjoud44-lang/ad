<template>
  <aside class="sidebar">
    <h1 class="sidebar-title">Admin Panel</h1>
    <nav>
      <ul class="sidebar-menu">
        <li><router-link to="/welcome" class="sidebar-item">Bienvenue</router-link></li>
        <li><router-link to="/responsables" class="sidebar-item">Responsables</router-link></li>
        <li><router-link to="/stagiaires" class="sidebar-item">Stagiaires</router-link></li>
        <li><router-link to="/parametres" class="sidebar-item">Paramètres</router-link></li>
        <li><router-link to="/logout" class="sidebar-item">Déconnexion</router-link></li>
      </ul>
    </nav>
  </aside>
</template>

<script>
export default {
  name: 'AdminDashboard'
}
</script>

<style scoped>
.sidebar {
  background-color: #2b2b2b;
  padding: 20px;
  color: white;
  font-family: 'Arial', sans-serif;
  box-shadow: 2px 0 5px rgba(0, 0, 0, 0.5);
}

.sidebar-title {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
  color: white;
}

.sidebar-menu {
  list-style: none;
  padding: 0;
}

.sidebar-item {
  color: white;
  text-decoration: none;
  font-size: 18px;
  padding: 10px;
  display: block;
  transition: background 0.3s, color 0.3s;
}

.sidebar-item:hover {
  background-color: #444;
  color: #ffcc00;
}
</style>
