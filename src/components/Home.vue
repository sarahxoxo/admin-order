<template>
  <div class="page-container">
    <div class="title">OVERVIEW</div>
    <div class="box-container d-flex">
      <div class="total-box col-md-4">
        <div><i class="fas fa-hand-holding-usd"></i>TOTAL REVENUE</div>
        <div class="num">54,540</div>
      </div>
      <div class="total-box col-md-4">
        <div><i class="fas fa-boxes"></i>TOTAL COST</div>
        <div class="num">12,660</div>
      </div>
      <div class="total-box col-md-4">
        <div><i class="fas fa-money-bill"></i>NET IMCOME</div>
        <div class="num">4,1880</div>
      </div>
    </div>
    <div class="box col-md-6">
      <div class="title">Transaction Website</div>
      <div class="list-item d-flex">
        <div class="icon col-md-4"><i class="fab fa-facebook"></i><span>Facebook.com</span></div>
        <div class="figure col-md-4">45,836</div>
        <div class="percent col-md-4"><i class="fas fa-arrow-up"></i>20%</div>
      </div>
    </div>
    <div class="box col-md-6">
      <div class="title">Latest Order</div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Home'
}
</script>
<style scoped>
.title {
  font-size: 24px;
  font-weight: bold;
}
.total-box {
  background: #fff;
  padding: 26px;
  text-align: center;
  margin: 0 20px 18px 0;
}
.num {
  font-size: 36px;
  font-weight: bold;
}
.total-box:first-child .num {
  color: var(--green-color);
}
.total-box:nth-child(2) .num {
  color: var(--red-color);
}
.total-box:nth-child(3) .num {
  color: var(--blue-color);
}
.box {
  padding: 30px 40px;
}
.list-item i {
  font-size: 45px;
}
.list-item span {
  color: var(--dark-gray);
}
.percent {
  color: var(--green-color);
}
.percent i {
  font-size: 17px;
}
</style>