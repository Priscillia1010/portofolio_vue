<template>
  <div>
    <h1 class="text-center pt-5">Contact</h1>
    <hr class="pb-3" />
    <div class="container">
      <div class="row text-center">
        <div class="col-12 mt-2">
          <form>
            <div class="kontak text-left">
              <p><strong>Nama</strong></p>
              <input type="text" placeholder="Masukan Nama" />
            </div>
            <div class="kontak text-left">
              <p><strong>Email</strong></p>
              <input type="text" placeholder="Masukan Email" />
            </div>
            <div class="kontak text-left">
              <p><strong>Nomor Telepon</strong></p>
              <input type="text" placeholder="Masukan Nomor Telepon" />
            </div>
            <div class="kontak text-left">
              <p><strong>Pesan</strong></p>
              <input class="pesan" type="text" placeholder="Masukan Pesan" />
            </div>
            <div class="kontak text-center">
              <button class="kirim">Kirim Pesan</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ContactMe",
};
</script>
<style scoped>
hr {
  width: 250px;
  border-top: 3px solid #999;
  margin-top: 20px;
  margin-bottom: 20px;
}

.kontak {
  align-items: center;
  line-height: 1px;
  margin-bottom: 30px;
  outline: black;
}

form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

input {
  width: 500px;
  height: 40px;
  padding: 6px 12px;
  font-size: 14px;
  border: 1.5px solid #ccc;
  border-radius: 5px;
}

.pesan {
  height: 200px;
  padding: 6px 12px;
  text-align: left;
  padding-bottom: 165px;
}

.kirim {
  width: 120px;
  height: 40px;
  background-color: gray;
  color: white;
  border-radius: 8px;
  border: none;
}
</style>
