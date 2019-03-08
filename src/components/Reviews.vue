<template>
  <section class="reviews text-center">
    <div class="row">
      <div class="review col-md-6 col-lg-3 mb-3 mb-sm-5">
        <div class="review__icon mb-4">
          <img src="../assets/PCG_Logo_HiRes.jpg" alt="PC Gamer logo">
        </div>
        <p class="review__text">
          <q>Offering real-world performance data is a great idea, and makes the process of ordering a PC much less abstract for newcomers than pick...</q>
        </p>
      </div>
      <div class="review col-md-6 col-lg-3 mb-3 mb-sm-5">
        <div class="review__icon mb-4">
          <h3>Forge</h3>
        </div>
        <p class="review__text">
          <q>BLD removes all the guesswork when it comes to building the perfect gaming PC for YOU. Their machines are fast, beatiful, and competitive...</q>
        </p>
      </div>
      <div class="review col-md-6 col-lg-3 mb-3 mb-sm-5">
        <div class="review__icon mb-4">
          <img src="../assets/logo_site_kotaku.png" alt="PC Gamer logo">
        </div>
        <p class="review__text">
          <q>There's something lovely about having a PC that comes with a set of guaranteed predicted frames-per-second targets for the games i planned...</q>
        </p>
      </div>
      <div class="review col-md-6 col-lg-3 mb-3 mb-sm-5">
        <div class="review__icon mb-4">
          <img src="../assets/techradar-logo.png" alt="PC Gamer logo">
        </div>
        <p class="review__text">
          <q>This is certanily a very neat idea, and the company is putting its money where its mouth is redaring the frame-rate estimations.</q>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "reviews"
};
</script>

<style lang="scss" scoped>
.reviews {
  background: black;
  color: white;
  padding: 10rem 5rem;

  .review {
    &__icon {
      h3 {
        font-size: 2.2rem;
        margin-bottom: 0;
        text-transform: uppercase;
        font-weight: 600;

        // @media only screen and (max-width: 580px) {
        //   margin-bottom: 4rem;
        // }
      }
    }
  }
}
</style>

