<template>
  <div>
    <Header></Header>
    <Features></Features>
    <Showcase></Showcase>
    <Info></Info>
    <Deals>></Deals>
    <Reviews></Reviews>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Features from "./components/Features";
import Showcase from "./components/Showcase";
import Info from "./components/Info";
import Deals from "./components/Deals";
import Reviews from "./components/Reviews";
import Footer from "./components/Footer";

export default {
  name: "app",
  components: {
    Header,
    Features,
    Showcase,
    Info,
    Deals,
    Reviews,
    Footer
  }
};
</script>

<style lang="scss">
*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}

html {
  font-size: 62.5%; // 1rem = 10px, 10px/16px = 62.5%
  overflow-x: hidden;

  @media only screen and (max-width: 1280px) {
    font-size: 60%;
  }
  @media only screen and (max-width: 1024px) {
    font-size: 57%;
  }
  @media only screen and (max-width: 768px) {
    font-size: 54%;
  }
  @media only screen and (max-width: 411px) {
    font-size: 52%;
  }
}

body {
  box-sizing: border-box;
  font-size: 1.4rem;
  font-family: "Roboto", sans-serif;
}
</style>
