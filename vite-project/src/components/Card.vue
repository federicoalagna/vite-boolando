<script>
export default {
  name: 'Card'
}</script>


<template>
      <div class="col-33">
    <div class="content">
      <img src="./img/2.webp" alt="2" />
      <img class="img2" src="./img/2b.webp" alt="1" />
      <div class="etichetta-sconto bg-red">-30%</div>
      <div class="cuore bg-white">&hearts;</div>
      <div class="marca">Guess</div>
      <div class="fit">ROSES TEE</div>
      <div class="prezzo">
        14,99 €
        <span class="old-price">20,99 €</span>
      </div>
    </div>
  </div>
</template>


<style>
.col-33 {
  margin: 10px;
  width: calc(100% / 3 - 20px);
} .content {
  position: relative;
} .etichetta-sconto {
  position: absolute;
  color: white;
  bottom: 95px;
  left: 0px;
  padding: 2px 10px;
  font-size: smaller;
} .etichetta-sostenibilità {
  position: absolute;
  color: white;
  bottom: 95px;
  left: 55px;
  padding: 2px 10px;
  font-size: smaller;
} .cuore {
  position: absolute;
  font-size: x-large;
  top: 10px;
  right: 0px;
  padding: 2px 10px;
} .marca {
  font-size: small;
  color: grey;
}

.fit {
  font-weight: 900;
}

.prezzo {
  font-size: small;
  color: red;
}

.old-price {
  color: grey;
  text-decoration: line-through;
}
</style>