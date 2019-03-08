<template>
  <header>
    <div class="auth-bar container-fluid d-flex justify-content-between px-lg-5">
      <a href="#" class="auth-bar__logo">
        <img class="img-fluid" src="../assets/logo-nzxt-black.png" alt="NZXT Logo">
      </a>
      <div>
        <a class="auth-bar__links" href="#">Log in</a>
        <a class="auth-bar__links" href="#">Sign up</a>
      </div>
    </div>

    <nav class="navbar mt-4 py-4 container-fluid px-lg-5">
      <ul class="navbar__list">
        <li class="navbar__item__img navbar-brand">
          <a href="#">
            <img src="../assets/logo-white.png" alt="BLD Logo">
          </a>
        </li>
        <li class="navbar__item nav-item">
          <a class="nav-link text-uppercase" href="#">What is BLD</a>
        </li>
        <li class="navbar__item nav-item">
          <a class="nav-link text-uppercase" href="#">Customer reviews</a>
        </li>
        <li class="navbar__item nav-item">
          <a class="nav-link text-uppercase" href="#">Support</a>
        </li>
        <li class="navbar__item nav-item">
          <a class="nav-link text-uppercase" href="#">Faq</a>
        </li>
      </ul>
      <a href="#" class="navbar__btn btn btn-outline-primary text-uppercase">Get started</a>
    </nav>
    <Hero></Hero>
  </header>
</template>

<script>
import Hero from "./Hero";

export default {
  name: "Header",
  components: {
    Hero
  }
};
</script>


<style lang="scss" scoped>
.auth-bar {
  margin-top: 3rem;

  &__logo {
    img {
      width: 10rem;
    }
  }

  &__links {
    color: #3dadad;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.6rem;
    text-transform: uppercase;

    &:last-child {
      margin-left: 2rem;
    }

    &:hover {
      text-decoration: underline;
    }
  }
}

.navbar {
  background: #3dadad;

  &__list {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    justify-content: space-around;
    align-items: center;
    margin-bottom: 0;
  }

  &__item {
    margin: 0 2rem;

    @media only screen and (max-width: 769px) {
      margin: 0 1rem;
    }

    &__img {
      margin-right: 3rem;

      @media only screen and (max-width: 750px) {
        margin: 0 1.5rem;
      }
    }
  }

  &__btn {
    font-size: 1.6rem;
    color: white;
    padding: 1rem 4rem;
    border: solid 3px white;
    border-radius: 5px;
    font-weight: 600;
    margin-left: auto;

    @media only screen and (max-width: 850px) {
      margin: 1rem auto 0;
    }

    &:hover {
      background: white;
      color: #3dadad;
    }
  }

  .nav-link {
    color: white;
    font-weight: 600;

    &:hover {
      text-decoration: underline;
    }
  }
}
</style>

