<template>
  <section class="hero jumbotron">
    <div class="hero__content container">
      <div class="row">
        <div class="hero__img col-md-6 col-sm-12">
          <img
            src="../assets/H500i_White Black new- hGPU-Purplelight.png"
            alt="H500i_White Black new"
            class="img-fluid"
          >
        </div>
        <div class="hero__text col-md-6 col-sm-12 text-md-left text-center">
          <div class="hero__logo my-5 mx-md-0 mx-sm-auto">
            <img class="img-fluid" src="../assets/bld-logo.png" alt="BLD by NZXT">
          </div>
          <h1 class="hero__heading display-3 mb-4 text-uppercase">Gaming pc's
            <br>made simple
          </h1>
          <p class="hero__catchphrase">Choose a game, set a budget and we'll BLD it</p>
          <a class="hero__btn btn text-uppercase" href="#">Get started</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "hero"
};
</script>

<style lang="scss" scoped>
.hero {
  background-color: rgba(0, 6, 12, 0.773);
  background-image: url("../assets/bg.png");
  background-size: cover;
  background-position: center;
  margin-bottom: 0;

  &__content {
    margin-top: 7rem;
    color: white;
    margin-bottom: 5rem;
  }

  &__heading {
    font-weight: 500;
  }

  &__logo {
    width: 25rem;

    @media only screen and (max-width: 580px) {
      margin: 0 auto;
    }
  }

  &__catchphrase {
    font-size: 2rem;
    opacity: 0.9;
    margin-bottom: 5rem;
  }

  &__btn {
    font-size: 1.6rem;
    background: #3dadad;
    padding: 1rem 5rem;
    color: white;
    font-weight: 500;

    &:hover {
      background: #3da0a0;
    }
  }
}
</style>

