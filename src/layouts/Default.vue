<template>
  <div>
    <div class="layout page">
      <Header />
      <slot/>
      <Footer />
    </div>
</div>
</template>

<script>
    import Header from '~/components/Header.vue'
    import Footer from '~/components/Footer.vue'
    export default {
      components: {
        Header,
        Footer
      },
    }
</script>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
  @font-face {
    font-family: 'Anaktoria';
    font-style: normal;
    font-weight: normal;
    src: local('Anaktoria'), url('../assets/fonts/Anaktoria.woff') format('woff');
    font-display: swap;
  }

  @font-face {
    font-family: 'Avenir';
    font-style: normal;
    font-weight: normal;
    src: local('Avenir'), url('../assets/fonts/Avenir-Regular.ttf') format('ttf');
    font-display: swap;
  }

  html, body, div, span, applet, object, iframe,
  h1, h2, h3, h4, h5, h6, p, blockquote, pre,
  a, abbr, acronym, address, big, cite, code,
  del, dfn, em, img, ins, kbd, q, s, samp,
  small, strike, strong, sub, sup, tt, var,
  b, u, i, center,
  dl, dt, dd, ol, ul, li,
  fieldset, form, label, legend,
  table, caption, tbody, tfoot, thead, tr, th, td,
  article, aside, canvas, details, embed, 
  figure, figcaption, footer, header, hgroup, 
  menu, nav, output, ruby, section, summary,
  time, mark, audio, video {
    /*font-family: Avenir;*/
    line-height: 1.9;
  } 
  .title {
    font-family: Anaktoria;
  }

  .page {
    min-height: 100vh;
  }

  .page > footer {
  position: sticky;
  top: 100vh;

  
}
</style>
