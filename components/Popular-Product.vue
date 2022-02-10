<template>
  <section>
    
    <div class="card mt-2 mb-2" @click="detail()">
      <div class="card-body">
        <div class="row">
          <div class="col-md-12 text-center">
            <img class="m-3" src="../assets/image/obh.png" width="100px" height="120px">
          </div>
        </div>
        <div class="row">
          <div class="col-md-12 text-center">
            <p style="color:#6A6767;font-weight:700;" class="ml-4 mr-4">OBH Combi Batuk dan Flu 60 ml</p>
            <p style="color:#16B3AC;font-weight:700"><b>Rp. 40.000,-</b></p>
            <hr>
          </div>
        </div>
        <!-- Apotek -->
        <div class="row">
          <div class="col-md-2 text-center">
            <img class="ml-auto" src="../assets/image/drugstore.png" width="25px" height="25px">
          </div>
          <div class="col-md-10">
            <p style="color:#16B3AC;font-size:15px;margin-top:3px">Apotek Watson</p>
          </div>
        </div>
        <!-- Location -->
        <div class="row">
          <div class="col-md-2 text-center">
            <i class="fa fa-map-marker " style="text-align: right;margin-left: 10px;font-size: 20px;color:#6A6767" aria-hidden="true"></i>
          </div>
          <div class="col-md-10 d-flex align-items-center">
            <p style="color:#6A6767;font-size:15px">Tangerang Selatan</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  methods: {
    detail() {
        this.$router.push({
          path: `/detail-produk`,
        })
      },
  },
}
</script>
