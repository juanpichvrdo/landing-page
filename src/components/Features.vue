<template>
  <section class="features">
    <div class="features__content container-fluid text-center px-5">
      <div class="row">
        <div class="feature col-md-6 col-lg-3" v-for="feature in features" :key="feature.heading">
          <div class="feature__icon">
            <img :src="feature.iconUrl" alt="Screwdriver icon">
          </div>
          <h3
            class="feature__heading display-4 font-weight-normal text-uppercase mb-4"
          >{{ feature.heading }}</h3>
          <p class="feature__text mb-4">{{ feature.text }}</p>
          <a href="#" class="feature__link text-uppercase">Learn more &gt;</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "features",
  data() {
    return {
      features: [
        {
          iconUrl: require("../assets/build-ico.png"),
          heading: "Tailored for games",
          text:
            "We've done the research and our algorithm takes care of the rest"
        },
        {
          iconUrl: require("../assets/glass.png"),
          heading: "Transparent pricing",
          text:
            "Customize your build with our curated parts with straight forward pricing and a flat $99 assembly fee."
        },
        {
          iconUrl: require("../assets/2year-ico.png"),
          heading: "All-in-one warranty",
          text:
            "All components under one warranty plan - NZXT will manage any problems for you."
        },
        {
          iconUrl: require("../assets/shipping-ico.png"),
          heading: "48-hour turnaround",
          text: "Get in the game quickly."
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
.features {
  background: rgb(245, 245, 245);
  background: linear-gradient(
    148deg,
    rgba(245, 245, 245, 1) 0%,
    rgba(98, 110, 119, 1) 0%,
    rgba(78, 86, 92, 1) 100%
  );

  &__content {
    padding: 6rem 0;
    color: white;
  }
  .feature {
    padding: 0 3rem;

    @media only screen and (max-width: 990px) {
      margin-bottom: 6rem;
    }

    &__icon {
      height: 10rem;

      img {
        width: 7rem;
      }
    }

    &__heading {
      line-height: 1.1;
    }

    &__text {
      line-height: 1.2;
      font-weight: 500;
    }

    &__link {
      color: white;
      font-weight: 600;
    }
  }
}
</style>

