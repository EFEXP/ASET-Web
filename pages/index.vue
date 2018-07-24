<template>
  <div>
  
    <section class="hero is-dark" id="top">
      <div class="hero-head">
          <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <h1 class="subtitle">ASET</h1>
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
   <div id="navbarExampleTransparentExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item" href="https://bulma.io/">
        Home
      </a>
      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link" href="/documentation/overview/start/">
          Menu
        </a>
        <div class="navbar-dropdown is-boxed">
          <a class="navbar-item" href="/documentation/overview/start/">
            Overview
          </a>
        </div>
      </div>
    </div>
     <div class="navbar-end">
      <div class="navbar-item">
        <div class="field is-grouped">
          <p class="control">
            <a class="bd-tw-button button  is-info" data-social-network="Twitter" data-social-action="tweet" data-social-target="http://localhost:4000" target="_blank" href="https://twitter.com/intent/tweet?text=Bulma: a modern CSS framework based on Flexbox&amp;hashtags=bulmaio&amp;url=http://localhost:4000&amp;via=jgthms">
              <span class="icon">
                <i class="fab fa-twitter"></i>
              </span>
              <span>
                Tweet
              </span>
            </a>
          </p>
          <p class="control">
            <a class="button is-primary" href="">
              <span class="icon">
                <i class="fas fa-handshake"></i>
              </span>
              <span>JOIN</span>
            </a>
          </p>
        </div>
      </div>
    </div>
     </div>
</nav>
      </div>
  <div class="hero-body">
    <div class="container has-text-centered">
      <h1 class="title">
        ASET
      </h1>
      <h2 class="subtitle">
        東京理科大学外来生物対策研究会
      </h2>
    </div>
  </div>
</section>
 <section class="content">
    <h1>私たちの活動</h1>
    <p>私たちの身近には数多くの外来種がいます。その多くは既存の生態系を破壊し、自然環境を単調でつまらないものへと変えてしまいます。</p>
    <p>基本的な目的は「在来種の保護」であり、目的達成の手段として外来生物の研究を進めていきます。</p>
    <p>
 </section>
    <section class="hero is-dark">
       <div class="hero-body">
    <div class="container has-text-centered">
      <h1 class="title">
        Alien Species
      </h1>
      <h2 class="subtitle">
        外来種
      </h2>
    </div>
  </div>
    </section>
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.subtitle{
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

#top{
   background:url(/sa.jpg) center no-repeat; background-size: cover;
}
</style>

