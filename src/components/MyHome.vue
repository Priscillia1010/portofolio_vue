<template>
  <div>
    <!-- home -->
    <div class="container-fluid">
      <div class="row text-center bg-secondary pt-3 text-white">
        <div class="col-12">
          <img
            class="profile"
            src="../assets/saya.jpg"
            style="width: 100px; height: 120px; -radius: 20px"
          />
          <h1>{{ home.nama }}</h1>
          <h4 class="pb-5">{{ home.job }}</h4>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name: "MyHome",
    data() {
      return {
        home: {},
      };
    },
    created() {
      let profile = {
        nama: "Priscillia Candra",
        job: "Student | Web Developer | Basketball Player" 
      };
      return(this.home = profile);
    },
};
</script>
<style scoped>
.profile {
  width: 100px;
  height: 120px;
  border: 2px solid white;
  border-radius: 20px;
}
</style>
