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
                <p class="font" style="font-size:15px"><b>Provinsi</b></p>
                <div>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Jawa Tengah
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Jawa Timur
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Jawa Barat
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    DKI Jakarta
                  </b-form-checkbox>
                  <nuxt-link to="">
                    <p class="mt-3" style="color:#16B3AC;font-size:15px" v-b-modal.modal-1>Lihat Lebih Lengkap</p>
                  </nuxt-link>
                </div>
                <p class="font" style="font-size:15px"><b>Kabupaten</b></p>
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
                    <p class="mt-3" style="color:#16B3AC;font-size:15px" v-b-modal.modal-2>Lihat Lebih Lengkap</p>
                  </nuxt-link>
                </div>
                <p class="font" style="font-size:15px"><b>Kecamatan</b></p>
                <div>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kec. Aceh Barat
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kec. Aceh Barat Daya
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kec. Aceh Selatan
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Kec. Aceh Jaya
                  </b-form-checkbox>
                  <nuxt-link to="">
                    <p class="mt-3" style="color:#16B3AC;font-size:15px">Lihat Lebih Lengkap</p>
                  </nuxt-link>
                </div>
                <p class="font" style="font-size:15px"><b>Apotek</b></p>
                <div>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Watson
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Halodoc
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Go Apotek
                  </b-form-checkbox>
                  <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
                    unchecked-value="not_accepted">
                    Century
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
                <div>
                  <b-button variant="primary" block size="sm">Terapkan</b-button>
                </div>
              </div>
          </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Modal Provinsi -->
     <b-modal id="modal-1" title="Provinsi">
      <div class="row">
        <div class="col-md-12">
          <p class="font"><b>Daftar Provinsi</b></p>
          <b-input-group size="sm" class="my-2 my-lg-0 my-lg-0">
              <b-form-input class="" placeholder="Cari nama Provinsi" aria-label="Search" style="width: 300px;">
              </b-form-input>
              <b-input-group-append>
                <nuxt-link to="/detail">
                <b-button size="sm" text="Button" variant="primary">Search</b-button>
                </nuxt-link>
              </b-input-group-append>
            </b-input-group>
        </div>
      </div>

      <br>
      <div class="row">
        <div class="col-md-6">
           <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              Jawa Tengah
            </b-form-checkbox>
            <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              Jawa Timur
            </b-form-checkbox>
            <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              Jawa Barat
            </b-form-checkbox>
            <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              DKI Jakarta
            </b-form-checkbox>
        </div>
        <div class="col-md-6">
           <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              Jawa Tengah
            </b-form-checkbox>
            <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              Jawa Timur
            </b-form-checkbox>
            <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              Jawa Barat
            </b-form-checkbox>
            <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted"
              unchecked-value="not_accepted">
              DKI Jakarta
            </b-form-checkbox>
        </div>
      </div>

    </b-modal>

    <!-- Modal Kabupaten -->
     <b-modal id="modal-2" title="Provinsi">
      <div class="row">
        <div class="col-md-12">
          <p class="font"><b>Daftar Provinsi</b></p>
          <b-input-group size="sm" class="my-2 my-lg-0 my-lg-0">
              <b-form-input class="" placeholder="Cari nama Kabupaten" aria-label="Search" style="width: 300px;">
              </b-form-input>
              <b-input-group-append>
                <nuxt-link to="/detail">
                <b-button size="sm" text="Button" variant="primary">Search</b-button>
                </nuxt-link>
              </b-input-group-append>
            </b-input-group>
        </div>
      </div>

      <br>
      <div class="row">
        <div class="col-md-6">
           <b-form-checkbox id="" >
              Kab Aceh
            </b-form-checkbox>
            <b-form-checkbox >
              Kab Purbolinggo
            </b-form-checkbox>
            <b-form-checkbox >
              Kab Pekalongan
            </b-form-checkbox>
            <b-form-checkbox >
              Kab Ungaran
            </b-form-checkbox>
        </div>
        <div class="col-md-6">
            <b-form-checkbox id="" >
              Kab Aceh
            </b-form-checkbox>
            <b-form-checkbox >
              Kab Purbolinggo
            </b-form-checkbox>
            <b-form-checkbox >
              Kab Pekalongan
            </b-form-checkbox>
            <b-form-checkbox >
              Kab Ungaran
            </b-form-checkbox>
        </div>
      </div>

    </b-modal>
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
