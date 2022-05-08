<template>
  <div class="main-sidebar">
    <aside id="sidebar-wrapper">
      <div class="sidebar-brand">
        <nuxt-link to="/dashboard">Nuxt-Tutorial {{this.login.username}} [{{this.login.id}}]{{this.login.no_pendaftaran}}</nuxt-link>
      </div>
      <div class="sidebar-brand sidebar-brand-sm">
        <a href="index.html">DASHBOARD</a>
      </div>
      <ul class="sidebar-menu">
        <li class="menu-header">Starter</li>
         <li class="nav-item dropdown">
          <a href="#" class="nav-link has-dropdown" data-toggle="dropdown"
            ><i class="fas fa-columns"></i> <span>Example</span></a>
          <ul class="dropdown-menu">
            <li>
              <nuxt-link class="nav-link" to="/Example/button">
                Action
              </nuxt-link>
            </li>
          </ul>
        </li>


        <li class="nav-item dropdown">
          <a href="#" class="nav-link has-dropdown" data-toggle="dropdown"
            ><i class="fas fa-columns"></i> <span>Components</span></a>
          <ul class="dropdown-menu">
            <li>
              <nuxt-link class="nav-link" to="/components/button">
                Button
              </nuxt-link>
            </li>
            <li>
              <nuxt-link class="nav-link" to="/components/checkbox">
                Checkbox
              </nuxt-link>
            </li>
             <li>
              <nuxt-link class="nav-link" to="/components/inputtext">
                Input Text
              </nuxt-link>
            </li>
            <li>
              <nuxt-link class="nav-link" to="/components/listbox">
                ListBox
              </nuxt-link>
            </li>
             <li>
              <nuxt-link class="nav-link" to="/components/radiobutton">
                Radio Button
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
          <nuxt-link class="nav-link" to="/tiu/"
            ><i class="far fa-square"></i> <span>TIU</span></nuxt-link
          >
        </li>
        <li>
          <nuxt-link class="nav-link" to="/papi/"
            ><i class="far fa-square"></i> <span>PAPI</span></nuxt-link
          >
        </li>
        <li>
          <nuxt-link class="nav-link" to="/riasec/"
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
<script>
export default {
  auth: false,
  layout: "blank",
  data() {
    return {
      //state post
      login: {
        id:"",
        username: "",
        password: "",
        no_pendaftaran: "",
      },
      //state validation
      validation: [],
    };
  },
  mounted(){
    if (localStorage.username){
      console.log(localStorage.username);
      this.login.username = localStorage.username
      this.login.id = localStorage.id
      this.login.no_pendaftaran = localStorage.no_pendaftaran
    }
  },
  methods: {
    //method "store"
    async store(e) {
    
    },
  },
};
</script>