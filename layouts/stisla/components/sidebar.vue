<template>
  <div class="main-sidebar">
    <aside id="sidebar-wrapper">
      <div class="sidebar-brand">
        <nuxt-link to="/dashboard">ONLINE PSIKOTEST</nuxt-link>
      </div>
      <div class="sidebar-brand sidebar-brand-sm">
        <a href="index.html">DASHBOARD</a>
      </div>
      <ul class="sidebar-menu">
        <li class="menu-header">Starter</li>
        <li class="nav-item dropdown">
          <a href="#" class="nav-link has-dropdown" data-toggle="dropdown">
            <i class="fas fa-columns"></i> <span>SETTING</span>
          </a>
          <ul class="dropdown-menu">
            <li>
              <nuxt-link class="nav-link" to="/example/export">
                User
              </nuxt-link>
            </li>
            <li>
              <nuxt-link class="nav-link" to="/example/export">
                Role
              </nuxt-link>
            </li>
          </ul>
        </li>
        <li>
          <nuxt-link class="nav-link" to="/dashboard/"
            ><i class="far fa-square"></i> <span>Dashboard</span></nuxt-link
          >
        </li>
        <li>
          <nuxt-link class="nav-link" to="/papi/test"
            ><i class="far fa-square"></i> <span>Papi</span></nuxt-link
          >
        </li>
        <li>
          <nuxt-link class="nav-link" to="/coba2/"
            ><i class="far fa-square"></i> <span>RIASEC</span></nuxt-link
          >
        </li>

        <li>
          <nuxt-link class="nav-link has-icon text-danger" to="/logout"
            ><i class="fas fa-sign-out-alt"></i> <span>Logout</span></nuxt-link
          >
        </li>
      </ul>
    </aside>
  </div>
</template>
