<template>
  <div>
    <h1 class="text-center pt-5">About</h1>
    <hr class="pb-3" />
    <div class="container">
      <div class="row text-center">
        <div class="col-md-6 col-sm-12">
          <p>
            Nama saya {{ about.nama }}. Saya lahir pada tanggal
            {{ about.tanggal }}. Saat ini, saya berdomisili di
            {{ about.tempat }}. Saya sekolah di {{ about.sekolah }} kelas
            {{ about.kelas }}. Saya akan melanjukan perguruan tinggi saya di
            {{ about.kuliah }} jurusan {{ about.jurusan }}.
          </p>
          <img
            class="sekolah"
            src="https://1.bp.blogspot.com/-x1uySxT7XQA/XYZxWyOQTmI/AAAAAAAALrI/aZUAYpbB7KgcpwzV_BkAZXKOEz7EdD4fACLcBGAsYHQ/s1600/01-49-44-1.jpg"
          />
        </div>
        <div class="col-md-6 col-sm-12">
          <p>
            Jurusan kuliah yang saya inginkan membuat {{ about.dorongan }} sejak
            saya berada di kelas 12. Saya berharap {{ about.harapan }} nantinya.
            Selain itu, saya juga memiliki hobi yaitu {{ about.hobi }} dan saya
            juga sering {{ about.kegiatan }}.
          </p>
          <img
            class="sekolah"
            src="https://th.bing.com/th/id/R.a283211d1ba87bb843118de51b6dd2ba?rik=6oSAF%2b702WOhfg&riu=http%3a%2f%2fbinus.edu%2fmuseum%2fwp-content%2fuploads%2f2021%2f06%2fWhatsApp-Image-2021-06-09-at-18.46.23-768x512.jpeg&ehk=qsXEhaoZSZA%2f2OxcRWxulonm1XtjPwCtPKXDgVVAa8A%3d&risl=&pid=ImgRaw&r=0"
          />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AboutMe",
  data() {
    return {
      about: {},
    };
  },
  created() {
    let biodata = {
      nama: "Priscillia Candra",
      tanggal: "10 Oktober 2005",
      tempat: "Kelapa Gading, Jakarta Utara",
      sekolah: "SMA Mahatma Gading, Jakarta Utara",
      kelas: "12 IPA",
      kuliah: "Binus University Kemanggisan",
      jurusan: "Computer Science",
      dorongan: "saya tertarik untuk belajar coding",
      harapan: "saya akan bisa menjadi programmer yang profesional",
      hobi: "bermain basket",
      kegiatan: "mengikuti pertandingan basket antar club",
    };
    return (this.about = biodata);
  },
};
</script>
<style scoped>
hr {
  width: 250px;
  border-top: 3px solid #999;
  margin-top: 20px;
  margin-bottom: 20px;
}

.sekolah {
  width: 300px;
  height: 200px;
  border: 5px solid gray;
  margin-top: 30px;
}
</style>
