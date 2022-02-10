<template>
  <section>
    <div>
      <b-navbar toggleable="lg" style="background-color:#fff">
        <div class="container">
          <b-navbar-brand href="/">
            <img src="../assets/image/logo.png" width="90px" height="">
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
              <b-nav-item-dropdown text="Kategori" class="ml-3" left>
                <b-dropdown-item class="" href="#">
                  <div class="row ">
                    <div class="col-md-3">
                      <img class="mt-3" src="../assets/image/medicine.png" width="20px" height="20px">
                    </div>
                    <div class="col-md-9 ">
                      <p class="mt-3"><b>Suplemen</b></p>
                    </div>
                  </div>
                </b-dropdown-item>
                <b-dropdown-item class="" href="#">
                  <div class="row ">
                    <div class="col-md-3">
                      <img class="mt-3" src="../assets/image/drugs.png" width="20px" height="20px">
                    </div>
                    <div class="col-md-9 ">
                      <p class="mt-3"><b>Obat</b></p>
                    </div>
                  </div>
                </b-dropdown-item>
                <b-dropdown-item class="" href="#">
                  <div class="row ">
                    <div class="col-md-3">
                      <img class="mt-3" src="../assets/image/herbal.png" width="20px" height="20px">
                    </div>
                    <div class="col-md-9 ">
                      <p class="mt-3"><b>Herbal</b></p>
                    </div>
                  </div>
                </b-dropdown-item>
                <b-dropdown-item class="" href="#">
                  <div class="row ">
                    <div class="col-md-3">
                      <img class="mt-3" src="../assets/image/batuk.png" width="20px" height="20px">
                    </div>
                    <div class="col-md-9 ">
                      <p class="mt-3"><b>Batuk dan Flu</b></p>
                    </div>
                  </div>
                </b-dropdown-item>
                <b-dropdown-item class="" href="#">
                  <div class="row ">
                    <div class="col-md-3">
                      <img class="mt-3" src="../assets/image/healthy-food.png" width="20px" height="20px">
                    </div>
                    <div class="col-md-9 ">
                      <p class="mt-3"><b>Nutrisi</b></p>
                    </div>
                  </div>
                </b-dropdown-item>
                <hr>
                <b-dropdown-item class="mb-2 text-center" href="#">
                  <p class="mt-3">lihat kategori lainnya</p>
                </b-dropdown-item>
                
              </b-nav-item-dropdown>
            </b-navbar-nav>
            <ul class="navbar-nav mr-auto ml-auto">
              <li class="nav-item">

                <b-input-group size="sm" class="my-2 my-lg-0 my-lg-0">
                  <b-form-input class="" placeholder="Cari Obat ..." aria-label="Search" style="width: 600px;">
                  </b-form-input>
                  <b-input-group-append>
                    <nuxt-link to="/detail">
                    <b-button size="sm" text="Button" variant="primary">Search</b-button>
                    </nuxt-link>
                  </b-input-group-append>
                </b-input-group>
              </li>
            </ul>

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
             <b-nav-item href="#"> <img class="ml-auto mr-2" src="../assets/image/drugstore.png" width="25px" height="25px">Apotek</b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </div>
      </b-navbar>
    </div>
  </section>
</template>
<style>
  .navbar-expand-lg {
    flex-flow: row nowrap;
    justify-content: flex-start;
    box-shadow: 0 4px 8px 0 rgba(116, 115, 115, 0.116), 0 6px 20px 0 rgba(112, 112, 112, 0.116);
  }

  .navbar-dark .navbar-nav .show>.nav-link,
  .navbar-dark .navbar-nav .active>.nav-link,
  .navbar-dark .navbar-nav .nav-link.show,
  .navbar-dark .navbar-nav .nav-link.active {
    color: #8c8585;
  }

  .navbar-light .navbar-nav .nav-link {
    color: rgba(0, 0, 0, 0.5);
    font-weight: 600;
  }

  .dropdown-menu {
    position: absolute;
    top: 100%;
    left: 0;
    z-index: 1000;
    display: none;
    float: left;
    min-width: 14rem;
    padding: 0.1rem 0;
    margin: 0.1rem 0 0;
    font-size: 1rem;
    color: #212529;
    text-align: left;
    list-style: none;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid rgba(0, 0, 0, 0.15);
    border-radius: 0.25rem;
}


</style>
