<template>
  <section >
        <div class="row">
          <div class="col-md-12">
            <div class="card" style="height:100%;background: #CBECF1;border:none">
              <div class="row">
                <div class="col-md-3">
                  <img src="../assets/image/banner.png" width="260px" height="250px">
                </div>
                <div class="col-md-9  d-flex align-items-center" style="color:#8B8888">
                  <div class="row">
                    <div class="col-md-12">
                       <h2><b>FarmaPlus</b></h2>
                      <h4>Find your medicine here</h4>
                      <br>
                      <img src="../assets/image/logo.png" width="100px" height="40px">
                      <img class="ml-2" src="../assets/image/bumn.png" width="115px" height="25px">
                    </div>
                  </div>                 
                </div>
              </div>
            </div>
          </div>
        </div>
        <br>
        <div class="row">
          <div class="col-md-6">
            <h6 ><b>Kategori</b></h6>
          </div>
          <div class="col-md-6 text-right">
            <h7 style="color:#16B3AC;">lihat kategori lainnya</h7>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col-md-3">
           <Kategori/>
          </div>
          <div class="col-md-3">
           <Kategori/>
          </div>
          <div class="col-md-3">
           <Kategori/>
          </div>
          <div class="col-md-3">
           <Kategori/>
          </div>
          <div class="col-md-3">
           <Kategori/>
          </div>
          <div class="col-md-3">
           <Kategori/>
          </div>
          <div class="col-md-3">
           <Kategori/>
          </div>
         
        </div>
        <br>
        <!-- Popular Product -->
        <div class="row">
          <div class="col-md-12">
            <h6><b>Perduk Terpopuler</b></h6>
          </div>
          
        </div>
        <div class="row mt-3">
          <div class="col-md-3">
            <Popular-Product/>
          </div>         
          <div class="col-md-3">
            <Popular-Product/>
          </div>  
          <div class="col-md-3">
            <Popular-Product/>
          </div>  
          <div class="col-md-3">
            <Popular-Product/>
          </div>  
        </div>
        <br>
        <!-- Apotek List -->
        <div class="row">
          <div class="col-md-6">
            <h6><b>Apotek Terdekat</b></h6>
          </div>
          <div class="col-md-6 text-right">
            <h7 style="color:#16B3AC;">lihat apotek lainnya</h7>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col-md-3">
            <Apotek/>
          </div>         
          <div class="col-md-3">
           <Apotek/>
          </div>  
          <div class="col-md-3">
            <Apotek/>
          </div>  
          <div class="col-md-3">
            <Apotek/>
          </div>  
        </div>
  </section>
</template>

<script>
import Default from '../layouts/default.vue'
export default {
  layout:'default',
  components:{
    Default,
  }
}
</script>

<style>
  
</style>