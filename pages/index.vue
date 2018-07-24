<template>
  <div>
  
    <section class="hero is-dark is-fullheight" id="top">
      <div class="hero-head">
        <toolbar/>

      </div>
  <div class="hero-body">
    <div class="container has-text-centered">
      <h1 class="title" id="title">
        ASET
      </h1>
      <h2 class="subtitle">
        東京理科大学外来生物対策研究会
      </h2>
    </div>
  </div>
</section>
  <section class="hero is-warning">
       <div class="hero-body">
    <div class="container has-text-centered">
     <span class="icon is-large">
  <i class="fas fa-3x fa-exclamation-triangle"></i>
</span>
      <h1 class="title">
        WE ARE SORRY, NOW UNDER CONSTRUCTION !
      </h1>
      <h2 class="subtitle">
         このWebサイトは現在工事中です。
      </h2>
    </div>
  </div>
    </section>
    <section class="hero is-dark">
       <div class="hero-body">
    <div class="container has-text-centered">
       <span class="icon is-large">
  <i class="fas fa-3x fa-utensils"></i>
</span>
      <h1 class="title">
        How To Cook Alien Species
      </h1>
      <h2 class="subtitle">
        傾向と対策
      </h2>
    </div>
  </div>
    </section>
    <footer class="footer">
  <div class="content has-text-centered">
    <p>
       &copy;{{ new Date().getFullYear() }} —  <strong>Alien Species Eliminate Team</strong> 
    </p>
  </div>
</footer>
  </div>
</template>

<script>
import Toolbar from "~/components/Toolbar.vue";
export default {
  components: {
    Toolbar
  }
};
</script>

<style>
#title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  letter-spacing: 1px;
}
#top {
  background: url(/sa.jpg) center no-repeat;
  background-size: cover;
}
</style>

