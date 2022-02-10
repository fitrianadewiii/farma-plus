<template>
  <section>
    <div class="card" style="height:100vh;background-color:#f5f5f5;border:none;box-shadow:none">
      <div class="card-body">
        <div class="row">
          <div class="col-md-12">
            <h6 style="color:#6A6767"><i class="fa fa-filter mr-2" style="font-size: 20px;color:#6A6767"
                aria-hidden="true"></i><b> Filter</b></h6>
            <hr>
            <div class="row row-height">
              <div class="col-md-12 left">
                <p class="font" style="font-size:15px"><b>Daerah</b></p>
                <div>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kab. Aceh Barat
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kab. Aceh Barat Daya
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kab. Aceh Selatan
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kab. Aceh Jaya
                  </b-form-checkbox>
                  <nuxt-link to="">
                    <p class="mt-3" style="color:#16B3AC;font-size:15px">Lihat Lebih Lengkap</p>
                  </nuxt-link>
                </div>
                <p class="font" style="font-size:15px"><b>Brand</b></p>
                <div>
                  <b-form-checkbox id="" v-model="status" name="" value="accepted" unchecked-value="not_accepted">
                    Microvalen
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Dexplain
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Sanmol
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Paracetamol
                  </b-form-checkbox>
                  <nuxt-link to="">
                    <p class="mt-3" style="color:#16B3AC;font-size:15px">Lihat Lebih Lengkap</p>
                  </nuxt-link>
                </div>
                <p class="font" style="font-size:15px"><b>Gol Obat</b></p>
                <div>
                  <b-form-checkbox id="" v-model="status" name="" value="accepted" unchecked-value="not_accepted">
                    Obat Bebas
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Obat Bebas Terbatas
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Dengan Resep Dokter
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Fitofarmaka
                  </b-form-checkbox>
                  <nuxt-link to="">
                    <p class="mt-3" style="color:#16B3AC;font-size:15px">Lihat Lebih Lengkap</p>
                  </nuxt-link>
                </div>
              </div>
          </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
  .row-height {
    height: 90vh;
  }

  /*Set up the columns with a 100% height, body color and overflow scroll*/

  .left {
    height: 90%;
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
