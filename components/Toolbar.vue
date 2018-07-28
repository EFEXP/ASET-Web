<template lang="pug">
nav.navbar(role='navigation', aria-label='main navigation')
  .navbar-brand
    a.navbar-item
      h1.subtitle ASET
    a.navbar-burger(role='button', aria-label='menu', aria-expanded='false')
      span(aria-hidden='true')
      span(aria-hidden='true')
      span(aria-hidden='true')
  .navbar-menu
    .navbar-start
      a.navbar-item
        | Home
      .navbar-item.has-dropdownis-hoverable
        a.navbar-link
          | Menu
        .navbar-dropdown.is-boxed
          a.navbar-item
            | Overview
    .navbar-end
      .navbar-item
        .field.is-grouped
          p.control
            a.bd-tw-button.button.is-info(data-social-network='Twitter', data-social-action='tweet', data-social-target='http://localhost:4000', target='_blank', href='https://twitter.com/Coderase')
              span.icon
                i.fab.fa-twitter
              span
                | Tweet
          p.control
            a.button.is-primary(href='https://twitter.com/Coderase')
              span.icon
                i.fas.fa-handshake
              span JOIN

</template>

<style>
</style>

