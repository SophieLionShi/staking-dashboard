<template>
  <footer class="hide-xs">
    <ul>
      <li>
        <router-link
          class="app-menu-item-small"
          to="/about"
          exact="exact"
          title="About"
          >About</router-link
        >
      </li>
      <li>
        <router-link
          class="app-menu-item-small"
          to="/careers"
          exact="exact"
          title="Careers"
          >Careers</router-link
        >
      </li>
      <li>
        <router-link
          class="app-menu-item-small"
          to="/security"
          exact="exact"
          title="Security"
          >Security</router-link
        >
      </li>
      <li>
        <router-link
          class="app-menu-item-small"
          to="/terms"
          exact="exact"
          title="Terms"
          >Terms of Service</router-link
        >
      </li>
      <li>
        <router-link
          class="app-menu-item-small"
          to="/privacy"
          exact="exact"
          title="Privacy"
          >Privacy Policy</router-link
        >
      </li>
    </ul>
  </footer>
</template>

<script>
export default { name: `tm-page-footer` }
</script>

<style scoped>
footer {
  width: 100%;
  padding: 3rem 0 0;
  margin-top: 1rem;
}

ul {
  display: flex;
  align-items: center;
  justify-content: center;
}

ul li {
  display: inline;
  padding: 0 0.5rem;
}

.app-menu-item-small {
  display: inline-block;
  justify-content: space-between;
  align-items: center;
  padding: 0.25rem 0;
  color: var(--dim);
  font-size: var(--sm);
}

.app-menu-item-small:hover {
  color: var(--link);
}
</style>
