<template>
  <section class="info container">
    <div class="row">
      <div class="info__text col-lg-6 col-md-12 text-lg-left text-center">
        <h2
          class="info__heading text-uppercase display-3 font-weight-normal mb-4"
        >Built by experts, with an eye for design.</h2>
        <p
          class="info__paragraph mb-5"
        >NZXT has more than 12 years of experience developing award winning, high-quality PC components. By using the very best components, assembled by highly-trained builders, we can deliver a meticulously crafted gaming PC, backed by a comprehensive 2-year warranty.</p>
        <a class="info__btn btn text-uppercase mt-4" href="#">Learn more</a>
      </div>
      <div class="info__img col-lg-6 col-md-12 text-center">
        <img class="img-fluid" src="../assets/footer-pc.png" alt>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Info"
};
</script>

<style lang="scss">
.info {
  margin-top: 6rem;

  @media only screen and (max-width: 770px) {
    margin-top: 5rem;
  }

  &__text {
    margin-top: 5rem;
  }

  &__paragraph {
    width: 92%;
  }

  &__img {
    @media only screen and (max-width: 1000px) {
      margin-top: 7rem;
    }
  }

  &__btn {
    font-size: 1.6rem;
    background: #3dadad;
    padding: 1rem 5rem;
    color: white;
    font-weight: 500;

    &:hover {
      background: #3da0a0;
      color: white;
    }
  }
}
</style>

