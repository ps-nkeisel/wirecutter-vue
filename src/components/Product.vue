<template>
  <div class="product-container">
    <h4 class="product-label">Top Pick</h4>
    <b-container>
      <b-row cols="2">
        <b-col>
          <div class="product-image text-center">
            <img
              src="../assets/product.png"
              alt="Product image"
            />
          </div>
        </b-col>
        <b-col>
          <div class="product-description">
            <div class="product-title text-center">
              <b-link href="#">
                <h3>Beats by Dre PowerBeats</h3>
              </b-link>
            </div>
            <p class="text-center">Apple/Beats</p>
            <p class="text-center"><b-badge variant="warning">Price: $299.95</b-badge></p>
            <b-alert show variant="success">Pros: Great battery life, incredible sound, comfortable</b-alert>
            <b-alert show variant="danger">Cons: Expensive, warranty, limited color choices</b-alert>
            <p>
              We absolutely loved the new 
              <b-link href="#">Beats by Dre PowerBeats </b-link>
              from Apple. They’re expensive, but worth every penny. When we tested them against other headphones in this price range, they really shined, and they’re great for exercise because they stay put and are water and sweat resistant.
            </p>
            <b-button variant="danger" class="w-100">Buy from Amazon: $299.95</b-button>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "Product"
};
</script>

<style>
.product-container {
  position: relative;
  padding: 1em 1.5em;
  box-sizing: border-box;
  box-shadow: 0 0 5px 0 hsla(0,0%,55.7%,.5);
  border: 0 solid rgba(0,0,0,0);
  background-color: #fff;
  max-width: 360px;
  margin: 3.5em auto 2em;

  max-width: 100%;
  margin-left: .5em;
  margin-right: .5em;
}
.product-container .product-label {
  font-size: 1.25rem;
  line-height: 1.25rem;
  font-family: "Serifa",georgia,serif;
  font-weight: 700;
  display: inline-block;
  position: absolute;
  top: -20px;
  left: -10px;
  margin: 0;
  padding: 9px 16px 8px 14px;
  color: #fff;
  background-color: #3358d5;
  box-shadow: 2px 2px 2px 0 rgba(0,0,0,.14);
}

.product-container .product-label:after {
  content: " ";
  display: block;
  position: absolute;
  left: -10px;
  bottom: -7px;
  border-color: rgba(0,0,0,0) #133091 rgba(0,0,0,0) rgba(0,0,0,0);
  border-style: inset solid inset inset;
  border-width: 0 10px 7px;
}
.product-title{
  font-family: Franklin,helvetica,sans-serif;
  font-weight: 700;
  line-height: normal;
  text-decoration: underline;
}
</style>
