<template>
  <div class="container mt-5">

    <h2 class="text-center mb-3">Portofolio Company NR</h2>
    <p class="text-center mb-5">
      Company NR menghadirkan mobil performa tinggi dengan desain modern dan teknologi masa depan.
    </p>

    <div class="text-center mb-5">
      <h4 class="text-warning">Featured Car</h4>
      <h3>NR-X Phantom</h3>
      <p>Mobil sport andalan dengan kecepatan tinggi dan desain agresif khas Company NR.</p>
    </div>

    <div class="row">

      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <img src="https://i.pinimg.com/736x/83/61/8f/83618f38a393a700278411af297cb243.jpg" class="card-img-top">
          <div class="card-body">
            <h5>Porsche</h5>
            <p>Mobil sport dengan performa tinggi dan desain agresif untuk pecinta kecepatan.</p>
            <button class="btn btn-dark">Detail</button>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <img src="hhttps://i.pinimg.com/1200x/55/d5/60/55d560dd8cb5895cd363b2c305da8f9a.jpg  " class="card-img-top">
          <div class="card-body">
            <h5>NR E-Line</h5>
            <p>Mobil listrik modern yang ramah lingkungan dengan teknologi canggih.</p>
            <button class="btn btn-dark">Detail</button>
          </div>
        </div>
      </div>

      <!-- CARD 3 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <img src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c" class="card-img-top">
          <div class="card-body">
            <h5>NR GT-R Legacy</h5>
            <p>Perpaduan mobil klasik dan modern dengan tenaga besar dan desain elegan.</p>
            <button class="btn btn-dark">Detail</button>
          </div>
        </div>
      </div>

    </div>

  </div>
</template>

<style scoped>

.card {
  transition: 0.3s;
  border-radius: 12px;
}

.card:hover {
  transform: scale(1.05);
  box-shadow: 0 12px 25px rgba(0,0,0,0.3);
}

.card {
  background-color: rgba(255,255,255,0.95);
}

.card img {
  height: 200px;
  object-fit: cover;
}

</style>