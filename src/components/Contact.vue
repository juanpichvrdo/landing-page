<template>
  <section class="contact container-fluid text-center">
    <div class="row">
      <div class="contact__input col-md-6 col-sm-12 mx-auto">
        <h2 class="contact__heading text-uppercase mb-3">
          Stay
          <span>In Touch</span>
        </h2>
        <input class="py-3 text-center" type="text" placeholder="Your Email Address">
      </div>
    </div>
    <div class="row">
      <div class="contact__copyright col-md-6 col-sm-12 text-left d-flex align-items-baseline">
        <img src="../assets/logo-nzxt.png" alt="NZXT Logo">
        2018. All Rights Reserved.
      </div>
      <div
        class="contact__privacy col-md-6 col-sm-12 d-flex align-items-baseline justify-content-around"
      >
        <a href="#" class="contact__link">Privacy Policy</a>
        <a href="#" class="contact__link">Terms Of Service</a>
        <a href="#" class="contact__link">English</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "contact"
};
</script>

<style lang="scss" scoped>
.contact {
  background: black;
  padding-top: 5rem;
  padding-bottom: 3rem;

  &__input {
    margin-bottom: 10rem;
    input {
      width: 90%;
      background: #363636;
      border: none;
      border-radius: 8px;
      color: #fff;
      font-size: 1.6rem;
    }
  }

  &__heading {
    font-size: 3rem;
    font-weight: 500;
    color: white;

    span {
      color: #808285;
    }
  }

  &__copyright {
    font-size: 1.2rem;
    color: #727272;
    padding: 0 10rem;

    @media only screen and (max-width: 1024px) {
      padding: 0 7rem;
    }
    @media only screen and (max-width: 770px) {
      padding: 0 5rem;
    }
  }

  &__privacy {
    padding-top: 2rem;
  }

  &__link {
    color: #d7e03f;
  }
}
</style>

