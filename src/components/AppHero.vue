<template>
  <h1 class="sr-only">Peek-a-Vue</h1>
  <img
    srcset="/images/title.png 2x, /images/title.png 1x"
    src="/images/title.png"
    alt="Peek-a-Vue"
    class="title mb-5"
  />
  <section :class="$style.description">
    <p>Bem vindo ao jogo da memória, ache as comnições e ganhe NFT!</p>
    <!-- <p :class="$style['powered-wrapper']">
      Powered by
      <a :class="$style['powered-link']" href="https://v3.vuejs.org/">
        <img
          :class="$style['powered-logo']"
          src="/images/vue-logo.svg"
          alt="Vue.js logo"
        />
        Vue.js 3
      </a>
      <span>, </span>
      <a
        :class="$style['powered-link']"
        href="https://www.netlify.com/?utm_source=github&utm_medium=peekavue-bh&utm_campaign=devex"
      >
        <img
          :class="$style['powered-logo']"
          src="/images/netliheart.svg"
          alt="Netlify Heart Logo"
        />
        Netlify
      </a>
      <span> & </span>
      <a
        :class="$style['powered-link']"
        href="https://www.github.com/bencodezen/peek-a-vue"
      >
        <img
          :class="$style['powered-logo']"
          src="/images/github-logo.svg"
          alt="GitHub Logo"
        />
        GitHub</a
      >
    </p> -->
  </section>
</template>

<style module>
.description {
  font-family: 'Titillium Web', sans-serif;
}

.description p {
  margin: 0;
  font-size: 1rem;
}

.description p:last-child {
  margin-top: 10px;
  margin-bottom: 30px;
  font-size: 0.9rem;
}

.powered-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 15px;
}

.powered-link {
  padding: 0 5px;
}

.powered-link:first-child,
.powered-link:last-child {
  padding-right: 0;
}

.powered-logo {
  width: 18px;
}

.title {
  padding-bottom: 30px;
}
</style>
