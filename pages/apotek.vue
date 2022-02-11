<template>
  <section>
    <div class="row mt-3 mb-3">
      <div class="col-md-12">
        <b-input-group size="sm" class="my-2 my-lg-0 my-lg-0">
          <b-form-input class="" placeholder="Cari Apotek" aria-label="Search" style="width: 300px;">
          </b-form-input>
          <b-input-group-append>
            <nuxt-link to="/detail">
              <b-button size="sm" text="Button" variant="primary">Search</b-button>
            </nuxt-link>
          </b-input-group-append>
        </b-input-group>
      </div>
    </div>
    <div class="row">
        <div class="col-md-12">
            <p><b>Daftar Apotek</b></p>
        </div>
    </div>
    <div class="row mt-1">
      <div class="col-md-3">
        <Apotek />
      </div>
      <div class="col-md-3">
        <Apotek />
      </div>
      <div class="col-md-3">
        <Apotek />
      </div>
      <div class="col-md-3">
        <Apotek />
      </div>
      <div class="col-md-3">
        <Apotek />
      </div>
    </div>
  </section>
</template>
