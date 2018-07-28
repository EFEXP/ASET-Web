<template lang="pug">
div
  section#top.hero.is-dark.is-fullheight
    .hero-head
      toolbar
    .hero-body
      .container.has-text-centered
        h1#title.title
          | ASET
        h2.subtitle
          | 東京理科大学外来生物対策研究会
  section.hero.is-warning
    .hero-body
      .container.has-text-centered
        span.icon.is-large
          i.fas.fa-3x.fa-exclamation-triangle
        h1.title
          | WE ARE SORRY, NOW UNDER CONSTRUCTION !
        h2.subtitle
          | このWebサイトは現在工事中です。
  section.hero.is-dark
    .hero-body
      .container.has-text-centered
        span.icon.is-large
          i.fas.fa-3x.fa-utensils
        h1.title
          | How To Cook Alien Species
        h2.subtitle
          | 傾向と対策
  footer.footer
    .content.has-text-centered
      p
        | ©{{ new Date().getFullYear() }} —  
        strong Alien Species Eliminate Team
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

