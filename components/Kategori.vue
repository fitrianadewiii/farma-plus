<template>
  <section>
      <div class="card m-2" @click="detail()" style="cursor:pointer">
        <div class="row">
          <div class="col-md-3">
            <img class="m-3" src="../assets/image/medicine.png" width="30px" height="30px">
          </div>
          <div class="col-md-9 d-flex align-items-center">
            <h6 class="font"> <b>Suplemen</b></h6>
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
          path: `/detail`,
        })
      },
  },
}
</script>
