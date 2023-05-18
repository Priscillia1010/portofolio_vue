<template>
  <div>
    <button
      type="button"
      class="btn"
      data-toggle="modal"
      data-target="#exampleModal"
    >
      Add Items
    </button>
    <!-- Modal -->
    <div
      class="modal fade"
      id="exampleModal"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Basketball Shoes</h5>
            <button
              type="button"
              class="x btn-danger"
              data-dismiss="modal"
              aria-label="Close-light"
            >
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <div class="add">
              <p class="enter">Enter Shoes</p>
              <input type="text" placeholder="Enter Shoes" />
            </div>
            <div class="add"><hr /></div>
            <div class="add">
              <p class="enter">Enter Price</p>
              <input type="text" placeholder="Enter Price" />
            </div>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-danger" data-dismiss="modal">
              Cancel
            </button>
            <button type="button" class="btn btn-primary">Add Items</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AddProduct",
};
</script>
<style scoped>
button {
  float: left;
  width: 120px;
  height: 40px;
  border-radius: 10px;
  border: none;
  color: white;
  font-family: sans-serif;
  font-weight: bold;
  background: #088178;
  outline: none;
}

.x {
  width: 40px;
  height: 40px;
}

input {
  width: 200px;
  height: 30px;
  border-radius: 5px;
  border: 1.5px solid lightgray;
}
</style>
