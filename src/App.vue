<template>
  <div id="app">
    <Navbar />
    <b-container class="pb-5">
      <Header />

      <h1 class="my-4">The Best Headphones For Exercise</h1>
      <p>
        We looked at hundreds of headphones nec velit consectetur, porta lacus a, sodales turpis. Donec
        vitae nibh ex. Pellentesque a viverra sapien, in dictum metus. 
        <a href="#">Vestibulum non turpis</a>
        in nunc faucibus
        ornare blandit et ante. Quisque non lacinia lacus. Phasellus rhoncus, erat eget vehicula placerat,
        odio odio tincidunt lectus, id ullamcorper lacus lectus et felis. Praesent orci orci, luctus at nibh ac,
        maximus pretium lorem.
      </p>
      <b-row class="my-4">
        <b-col align-self="center" class="text-center">
          <img alt="Product" src="./assets/banner.png">
        </b-col>
      </b-row>
      <h2>Testing Process</h2>
      <p>
        Donec volutpat vulputate est a convallis. Phasellus a orci mauris. Nulla tristique molestie nisi ut
        iaculis. Suspendisse rutrum est eu quam vehicula, ut vehicula magna blandit. Cras dapibus
        elementum neque, id tempus turpis convallis vitae. Nulla quis augue sit amet nibh consectetur
        bibendum.
      </p>
      <p>
        Aenean tincidunt lobortis ultricies. Nulla consectetur at metus sed aliquam. Vivamus tempus porttitor
        nunc, nec egestas dolor dictum vitae. Phasellus malesuada erat et consequat lacinia. In eu mi non
        est semper tempus ac eu turpis. Donec elit purus, volutpat quis est nec, bibendum viverra nulla. Ut
        feugiat suscipit cursus. Phasellus luctus in ipsum fringilla scelerisque. Donec vehicula sem non
        massa finibus porttitor
      </p>
      <p>
        nterdum et malesuada fames ac ante ipsum primis in faucibus. Morbi justo nunc, tincidunt quis
        ipsum a, tempus lacinia libero. Nulla laoreet, dolor sit amet vehicula pellentesque, lorem felis
        eleifend ipsum, ac aliquam lacus felis ac metus. Morbi posuere nec tellus vitae sollicitudin. Etiam
        fringilla nulla ac nulla interdum, eu sagittis enim accumsan. Mauris tincidunt libero at pulvinar
        condimentum. Nunc non magna pulvinar, aliquam enim sit amet, ultricies mauris. Vestibulum
        rhoncus, magna sed bibendum fermentum.
      </p>

      <Product />

      <h2>How We Decided</h2>
      <p>
        Ut faucibus nibh magna. Mauris libero justo, aliquam et posuere nec, ultricies at nibh. Pellentesque
        pharetra, est ut placerat pulvinar, enim turpis feugiat nisi, a viverra justo augue eget leo. Donec
        ultrices venenatis velit fermentum cursus. Proin maximus at libero eu volutpat. Fusce ullamcorper et
        enim id imperdiet. Integer felis felis, volutpat auctor elit at, venenatis egestas elit. In hac habitasse
        platea dictumst.
      </p>

      <h2>Why You Should Trust Us</h2>
      <p>
        Proin elementum faucibus tincidunt. Nullam sed orci et lacus luctus pharetra. Quisque iaculis metus
        quis sem commodo, nec rhoncus tellus ornare. Nam non volutpat massa, eget ultrices neque.
        Pellentesque semper pharetra magna eu posuere. Maecenas pretium turpis nec lectus ornare, a
        tempor dui maximus. Aliquam dignissim sollicitudin fringilla. Proin vehicula tincidunt dui, vitae lacinia
        magna egestas ac. Ut et risus ut nulla rhoncus ultrices.
      </p>

      <h2>Runner Up Products</h2>
      <p>
        We also liked these products 
        <a href="#">maximus odio in molestie sodales</a>
        . Nulla facilisi. 
        <a href="#">Fusce ac</a>
         malesuada
        mi. Nulla et eros bibendum, tempus velit a, fringilla ligula. Cras cursus feugiat mi, laoreet laoreet
        ante scelerisque et. Maecenas efficitur elit nec facilisis aliquam. 
        <a href="#">Praesent gravida,</a>
         mauris ut
        ullamcorper tristique, metus ligula efficitur purus, ac laoreet purus odio vel urna. Integer placerat eu
        nisi pellentesque egestas.
      </p>
      <hr class="my-4" />

      <b-card header="Other reviews you may like:">
        <b-list-group>
          <b-list-group-item href="#" variant="light">
            <b-link href="#">Nam non volutpat massa</b-link>
            , eget ultrices neque. Pellentesque semper pharetra magna eu posuere.
          </b-list-group-item>
          <b-list-group-item href="#" variant="light">
            <b-link href="#">Nulla et eros bibendum</b-link>
            , tempus velit a, fringilla ligula. Cras cursus feugiat mi, laoreet laoreet ante scelerisque et.
          </b-list-group-item>
          <b-list-group-item href="#" variant="light">
            <b-link href="#">Proin elementum faucibus</b-link>
            tincidunt. Nullam sed orci et lacus luctus pharetra. Quisque iaculis metus quis.
          </b-list-group-item>
        </b-list-group>
      </b-card>
    </b-container>
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Product from './components/Product.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    Footer,
    Product
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
