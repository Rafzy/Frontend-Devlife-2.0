<template>
  <div class="main-sidebar">
        <aside id="sidebar-wrapper">
          <div class="sidebar-brand">
            <img src="@/assets/images/logo.png" alt="app-logo" width="30" class="mb-2">
            <h4 class="d-inline-block ml-3 mt-4">Devector</h4>
          </div>
          <section class="profile">
            <div class="profile-picture mb-3 ">
              <img class="mt-3" src="@/assets/images/pp.png" alt="profile-picture" width="85">
              <h6 class="mt-2 ff-poopins">{{ dataUser.nis }}</h6>
              <h4 class="ff-poopins">{{ dataUser.name }}</h4>
              <h6 class="ff-poopins">{{ dataUser.jurusan }}</h6>
            </div>
          </section>
          <ul class="sidebar-menu">
              <li class="menu-header my-2 mt--1">Menu</li>
              <li class="nav-item mt--1">
                <router-link :to="{ name: 'Dashboard' }" class="nav-link"><i class="fas fa-fire text-left"></i><span>Dashboard</span></router-link>
              </li>
              <li class="nav-item mt--1">
                <router-link :to="{ name: 'Absensi' }" class="nav-link"><i class="fas fa-user-check"></i><span>Absensi</span></router-link>
              </li>
              <li class="nav-item mt--1">
                <router-link :to="{ name: 'Jadwal' }" class="nav-link"><i class="far fa-clock"></i><span>Jadwal</span></router-link>
              </li>
              <li class="nav-item mt--1">
                <router-link :to="{ name: 'Guru' }" class="nav-link"><i class="fas fa-graduation-cap"></i><span>Guru Mapel</span></router-link>
              </li>
              <li class="nav-item mt--1">
                <router-link :to="{ name: 'Izin' }" class="nav-link"><i class="fas fa-user-friends"></i><span>Izin/Sakit</span></router-link>
              </li>
              <li class="nav-item down mt--1">
                <router-link :to="{ name: 'Settings' }" class="nav-link"><i class="fas fa-cog"></i><span>Settings</span></router-link>
              </li>
              </ul>
        </aside>
      </div>
</template>

<script>

export default {
    name: 'Navbar',
    data() {
        return {
            dataUser: []
        }
    },
    mounted() {
        this.getData()
    },
    methods: {
        getData() {
            this.dataUser = JSON.parse(localStorage.getItem('user'))
            console.log('ini response user', this.dataUser)
        }
    }
}

</script>

<style scoped>
.ff-poopins{
    font-family: 'Poppins', sans-serif;
}

.mt--1{
    margin-top: 0px;
}

h6 {
  font-size: 15px;
  font-weight: 500 !important;
}
.main-sidebar {
  position: fixed;
}
.nav-link.exact-active.active {
  background-color: #4e4081;
  color: white;
}
</style>
