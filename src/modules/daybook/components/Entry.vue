<template>
  <div class="mb-3 pointer p-2 entry-container"
    @click="$router.push( {name: 'entry', params: { id: 10 }} )"
  >

      <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">julio</span>
        <span class="mx-2 fw-light">2021, jueves</span>
      </div>

      <div class="entry-description">
          Aliquip elit deserunt elit do excepteur et. Amet laborum dolor mollit amet consectetur reprehenderit et sunt sunt non. Laboris exercitation laborum laboris aliquip et id do proident nostrud duis anim non incididunt.
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3350;
    transition: .2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45%);
        transition: .2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}
</style>