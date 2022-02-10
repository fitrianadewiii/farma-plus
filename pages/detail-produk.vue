<template>
  <section>
    <div class="row">
      <div class="col-md-12">
        <b-breadcrumb :items="items"></b-breadcrumb>
      </div>
      <div class="row">
        <div class="col-md-9">
          <div class="row mt-3">
            <div class="col-md-4">
              <img class=" mr-auto" src="../assets/image/obh.png" width="70%">
            </div>
            <div class="col-md-8">
              <h5 class="font"><b>OBH Combi Obat Flu dan Batuk 60 ML</b></h5>
              <h6>Rama OBH merupakan sirup yang berkhasiat meredakan batuk berdahak.</h6>

              <b-button variant="danger" size="" class="receipt text-center mt-2 mb-2">! Konsultasi dengan dokter
              </b-button>

              <h5 class="mt-3" style="color:#16B3AC"><b>Rp. 40.000,-</b></h5>
              <h6 class="mt-3" style="color:#16B3AC"><b>Obat flu dan batuk</b></h6>

              <hr>
            </div>
          </div>
          <br>
          <h6 class="font"><b>Deskripsi</b></h6>
          <h7 class="mt-3 font" style="text-align:justify">
            OBH COMBI PLUS BATUK FLU merupakan obat batuk dengan kandungan OBH, Paracetamol, Ephedrine HCl, dan
            Chlorphenamine maleat yang digunakan untuk meredakan batuk disertai gejala-gejala flu seperti demam, sakit
            kepala, hidung tersumbat, dan bersin-bersin. OBH bekerja sebagai ekspektoran atau peluruh dahak, Paracetamol
            digunakan sebagai pereda demam dan sakit kepala, Chlorpheniramine maleate bekerja sebagai antihistamin atau
            anti alergi untuk meredakan gejala alergi, dan Ephedrine HCl sebagai dekongestan hidung atau melonggarkan
            saluran pernafasan.

          </h7>
          <br>
          <br>
          <h6 class="font"><b>Indikasi Umum</b></h6>
          <h7 class="mt-3 font" style="text-align:justify">
            Meredakan batuk berdahak
          </h7>
          <br>
          <br>
           <h6 class="font"><b>Dosis Pemakaian </b></h6>
          <h7 class="mt-3 font" style="text-align:justify">
            Dewasa: 3-4 x sehari 1 sendok makan. Anak: 3-4 x sehari 1 sendok teh.
          </h7>
          
         


        </div>
        <div class="col-md-3">
          <Apotek />
          <h6 class="font mt-3 mb-3"><b>Produk Serupa</b></h6>
          <div class="row row-height">
            <div class="col-md-12 left">
              <Popular-product />
              <Popular-product />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
  import PopularProduct from '../components/Popular-Product.vue'
  export default {
    components: {
      PopularProduct
    },
    data() {
      return {
        items: [{
            text: 'Beranda',
            href: '#'
          },
          {
            text: 'Hasil Pencarian',
            href: '#'
          },
          {
            text: 'Detail Produk',
            active: true
          }
        ]
      }
    }
  }

</script>
<style>
  .receipt {
    background-color: rgba(209, 55, 55, 0.24);
    color: #CD1414;
    border: none;
    padding: 5px
  }

</style>
