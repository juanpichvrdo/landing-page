<template>
  <section class="deals mt-5 text-center">
    <div class="container">
      <h2 class="deals__heading text-uppercase display-4">Check out deals on refurbished builds</h2>
      <a class="deals__btn text-uppercase mt-4" href="#">Learn more</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "deals"
};
</script>

<style lang="scss" scoped>
.deals {
  background: #3dadad;
  color: white;
  padding: 4rem 0;

  &__heading {
    font-weight: 500;
  }

  &__btn {
    display: inline-block;
    margin-top: 5rem;
    font-size: 1.6rem;
    background: white;
    padding: 1rem 5rem;
    color: black;
    font-weight: 500;
    border-radius: 5px;
    transition: all 0.3s;

    &:hover {
      text-decoration: none;
      background: rgb(234, 234, 240);
    }
  }
}
</style>

