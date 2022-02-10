<template>
  <section>
    <div class="row">
      <div class="col-md-12">
          <b-breadcrumb :items="items"></b-breadcrumb>
      </div>
    </div>
     <div class="row " style="">
       <div class="col-md-3 " style="">
        <Filter-Obat/>
       </div>
       <div class="col-md-9 left">
         <div class="row mt-2">
           <div class="col-md-12">
             <p class="font">Berikut hasil pencarian <b>"OBH"</b></p>
             <hr>
           </div>
         </div>
         <div class="row ">
           <div class="col-md-6 d-flex align-items-center">
             <h6 style="color:#6A6767" class="mr-2"><i class="fa fa-sort mr-2" style="font-size: 15px;color:#6A6767" aria-hidden="true"></i> urutkan</h6>
          
              <b-dropdown id="dropdown-1" text="Lokasi" class="mr-2 " variant="" size="sm" >
                <b-dropdown-item>Lokasi : Dekat ke Jauh</b-dropdown-item>
                <b-dropdown-item>Lokasi : Jauh ke Dekat</b-dropdown-item>
              </b-dropdown>

               <b-dropdown id="dropdown-1" text="Harga" class=" " variant="" size="sm" >
                <b-dropdown-item>Harga : Rendah ke Tinggi</b-dropdown-item>
                <b-dropdown-item>Harga : Tinggi ke Rendah</b-dropdown-item>
              </b-dropdown>
           </div>
         </div>
         <div class="row row-height mt-3">
           <div class="col-md-12 left">
              <div class="row">
                <div class="col-md-6">
                  <Medicine/>
                </div>
                <div class="col-md-6">
                  <Medicine/>
                </div>
                <div class="col-md-6">
                  <Medicine/>
                </div>
                <div class="col-md-6">
                  <Medicine/>
                </div>
                <div class="col-md-6">
                  <Medicine/>
                </div>
              </div>
           </div>
         </div>
        
         
       </div>
     </div>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          {
            text: 'Beranda',
            href: '#'
          },
          {
            text: 'Hasil Pencarian',
            active: true
          }
        ]
      }
    }
  }
</script>
<style>
  .font{
    color:#6A6767
  }
  .h1.h2.h3.h4.h5.h6{
    color:#6A6767
  }
  /*Set the row height to the viewport*/
.row-height{
  height: 100vh;
}

/*Set up the columns with a 100% height, body color and overflow scroll*/

.left{
  height: 100%;
  overflow-y: scroll;
}



/*Remove the scrollbar from Chrome, Safari, Edge and IE*/
::-webkit-scrollbar {
    width: 0px;
    background: transparent;
}

* {
  -ms-overflow-style: none !important;
}
</style>
