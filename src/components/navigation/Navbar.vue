<template>
  <nav class="navbar navbar-expand-lg main-navbar">
      <form class="form-inline mr-auto">
        <ul class="navbar-nav mr-3">
          <li><a href="#" data-toggle="sidebar" class="nav-link nav-link-lg"><i class="fas fa-bars"></i></a></li>
          <li><a href="#" data-toggle="search" class="nav-link nav-link-lg d-sm-none"><i class="fas fa-search"></i></a></li>
        </ul>
        <div class="search-element">
          <input class="form-control mt-3" type="search" placeholder="Search" aria-label="Search" data-width="250">
          <button class="btn" type="submit"><i class="fas fa-search"></i></button>
          <div class="search-backdrop"></div>
          <div class="search-result">
            <div class="search-header">
              Riwayat
            </div>
            <div class="search-item">
              <a href="#">B.Indonesia</a>
              <a href="#" class="search-close"><i class="fas fa-times"></i></a>
            </div>
            <div class="search-item">
              <a href="#">Absen Matematika</a>
              <a href="#" class="search-close"><i class="fas fa-times"></i></a>
            </div>
            <div class="search-item">
              <a href="#">Total Izin</a>
              <a href="#" class="search-close"><i class="fas fa-times"></i></a>
            </div>
            <div class="search-header">
              Mapel Kejuruan
            </div>
            <div class="search-item">
              <a href="#">
                <img class="mr-3 rounded" width="30" src="">
                Teknik Komputer dan Informatika
              </a>
            </div>
            <div class="search-item">
              <a href="#">
                <img class="mr-3 rounded" width="30" src="">
                Elektronika
              </a>
            </div>
            <div class="search-item">
              <a href="#">
                <img class="mr-3 rounded" width="30" src="">
                Teknik Ketenagalistrikan
              </a>
            </div>
            <div class="search-header">
              Projek Kejuruan
            </div>
            <div class="search-item">
              <a href="#">
                <div class="search-icon bg-danger text-white mr-3">
                  <i class="fas fa-code"></i>
                </div>
                Pengembangan Perangkat Lunak dan Gim
              </a>
            </div>
            <div class="search-item">
              <a href="#">
                <div class="search-icon bg-primary text-white mr-3">
                  <i class="fas fa-laptop"></i>
                </div>
                Desain Komunikasi Visual
              </a>
            </div>
          </div>
        </div>
      </form>
      <ul class="navbar-nav navbar-right">
        <li class="dropdown dropdown-list-toggle"><a href="#" data-toggle="dropdown" class="nav-link nav-link-lg message-toggle beep"><i class="far fa-envelope"></i></a>
          <div class="dropdown-menu dropdown-list dropdown-menu-right">
            <div class="dropdown-header">Pesan
              <div class="float-right">
                <a href="#">Tandai semua telah dibaca</a>
              </div>
            </div>
            <div class="dropdown-list-content dropdown-list-message">
              <a href="#" class="dropdown-item dropdown-item-unread">
                <div class="dropdown-item-avatar">
                  <img alt="image" src="@/assets/images/user3.jpg" class="rounded-sm">
                  <div class="is-online"></div>
                </div>
                <div class="dropdown-item-desc">
                  <b>Kusnaedi</b>
                  <p>Hello, Bro!</p>
                  <div class="time">10 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item dropdown-item-unread">
                <div class="dropdown-item-avatar">
                  <img alt="image" src="@/assets/images/user4.jpg" class="rounded-sm">
                </div>
                <div class="dropdown-item-desc">
                  <b>Dedik Sugiharto</b>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
                  <div class="time">12 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item dropdown-item-unread">
                <div class="dropdown-item-avatar">
                  <img alt="image" src="@/assets/images/user2.jpg" class="rounded-sm">
                  <div class="is-online"></div>
                </div>
                <div class="dropdown-item-desc">
                  <b>Agung Ardiansyah</b>
                  <p>Sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                  <div class="time">12 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item">
                <div class="dropdown-item-avatar">
                  <img alt="image" src="" class="rounded-circle">
                </div>
                <div class="dropdown-item-desc">
                  <b>Ardian Rahardiansyah</b>
                  <p>Duis aute irure dolor in reprehenderit in voluptate velit ess</p>
                  <div class="time">16 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item">
                <div class="dropdown-item-avatar">
                  <img alt="image" src="" class="rounded-circle">
                </div>
                <div class="dropdown-item-desc">
                  <b>Alfa Zulkarnain</b>
                  <p>Exercitation ullamco laboris nisi ut aliquip ex ea commodo</p>
                  <div class="time">Kemarin</div>
                </div>
              </a>
            </div>
            <div class="dropdown-footer text-center">
              <a href="#">Lihat semua <i class="fas fa-chevron-right"></i></a>
            </div>
          </div>
        </li>
        <li class="dropdown dropdown-list-toggle"><a href="#" data-toggle="dropdown" class="nav-link notification-toggle nav-link-lg beep"><i class="far fa-bell"></i></a>
          <div class="dropdown-menu dropdown-list dropdown-menu-right">
            <div class="dropdown-header">Notifikasi
              <div class="float-right">
                <a href="#">Tandai semua telah dibaca</a>
              </div>
            </div>
            <div class="dropdown-list-content dropdown-list-icons">
              <a href="#" class="dropdown-item dropdown-item-unread">
                <div class="dropdown-item-icon bg-primary text-white">
                  <i class="fas fa-code"></i>
                </div>
                <div class="dropdown-item-desc">
                    <b>Pembaruan baru untuk sistem</b>
                  <div class="time text-primary">2 menit lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item">
                <div class="dropdown-item-icon bg-info text-white">
                  <i class="far fa-user"></i>
                </div>
                <div class="dropdown-item-desc">
                  <b>Kamu</b> and <b>Dedik Sugiharto</b> sekarang berteman
                  <div class="time">10 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item">
                <div class="dropdown-item-icon bg-success text-white">
                  <i class="fas fa-check"></i>
                </div>
                <div class="dropdown-item-desc">
                  <b>Berhasil mengisi absensi</b>
                  <div class="time">12 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item">
                <div class="dropdown-item-icon bg-danger text-white">
                  <i class="fas fa-exclamation-triangle"></i>
                </div>
                <div class="dropdown-item-desc">
                  Perbarui profil Anda
                  <div class="time">17 jam lalu</div>
                </div>
              </a>
              <a href="#" class="dropdown-item">
                <div class="dropdown-item-icon bg-info text-white">
                  <i class="fas fa-bell"></i>
                </div>
                <div class="dropdown-item-desc">
                  Selamat datang di Devactor
                  <div class="time">Kemarin</div>
                </div>
              </a>
            </div>
            <div class="dropdown-footer text-center">
              <a href="#">Lihat semua <i class="fas fa-chevron-right"></i></a>
            </div>
          </div>
        </li>
        <li class="dropdown"><a href="#" data-toggle="dropdown" class="nav-link dropdown-toggle nav-link-lg nav-link-user">
          <img alt="image" src="@/assets/images/user1.jpg" class="rounded-circle mr-1">
          <div class="d-sm-none d-lg-inline-block">Hi, {{ user.name}}</div></a>
          <div class="dropdown-menu dropdown-menu-right">
            <div class="dropdown-title">Masuk 5 menit yang lalu</div>
            <a href="features-profile.html" class="dropdown-item has-icon">
              <i class="far fa-user"></i> Profil
            </a>
            <a href="features-activities.html" class="dropdown-item has-icon">
              <i class="fas fa-bolt"></i> Aktifitas
            </a>
            <a href="features-settings.html" class="dropdown-item has-icon">
              <i class="fas fa-cog"></i> Pengaturan
            </a>
            <div class="dropdown-divider"></div>
            <a href="#" class="dropdown-item has-icon text-danger" @click="logout">
              <i class="fas fa-sign-out-alt"></i> Keluar akun
            </a>
          </div>
        </li>
      </ul>
    </nav>
</template>

<script>
export default {
    name: 'Navbar',
    data(){
        return {
            user: []
        }
    },
    mounted() {
        this.getData()
    },
    methods: {
        logout() {
            this.$store.dispatch('logout')
                .then(() => {
                    this.$router.push({ name: 'Sign In'})
                })
        },
        getData() {
            this.user = JSON.parse(localStorage.getItem('user'))
            console.log('ini response user', this.user)
        }
    }
}
</script>

<style scoped>
.main-sidebar {
  position: fixed;
}
</style>