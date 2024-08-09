<template>
  <div class="contenair">
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/id/200/320/200" 
          class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/id/201/320/200" 
          class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/id/203/320/200" 
          class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppCards'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.contenair{
  display: flex;
}
.col-md-4 {
  flex: 0 0 auto;
  width: 71.3%;
  margin: auto;
}
</style>