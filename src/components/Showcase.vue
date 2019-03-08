<template>
  <section class="showcase row text-center">
    <div class="showcase__ninja col-lg-6 col-md-12">
      <h3 class="showcase__heading text-uppercase display-4 mt-5">Ninjas fortnite build</h3>
      <a href="#" class="showcase__link text-uppercase">Learn more &gt;</a>
      <div class="showcase__img mt-5">
        <img class="img-fluid" src="../assets/Group 99.png" alt="Ninja logo">
      </div>
    </div>
    <div class="showcase__pubg col-lg-6 col-md-12">
      <h3 class="showcase__heading text-uppercase display-4 mt-5">Limited edition pubg case</h3>
      <a href="#" class="showcase__link text-uppercase">Learn more &gt;</a>
      <div class="showcase__img mt-5">
        <img
          class="img-fluid"
          src="../assets/Player-Unknown-Battlegrounds-Logo.png"
          alt="PUBG Logo"
          width="300"
        >
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "showcase"
};
</script>

<style lang="scss" scoped>
.showcase {
  color: white;

  &__ninja {
    background: #3dadad;
    padding: 0rem 6rem 10rem;
  }

  &__pubg {
    background-image: url("../assets/Group 9.jpg");
    background-size: cover;
    background-position: center;
    padding: 0rem 6rem 10rem;
  }

  &__heading {
    font-weight: 500;
  }

  &__link {
    color: white;
  }
}
</style>

