<template>
  <footer class="footer">
    <div class="categories container-fluid">
      <div class="row">
        <ul class="category col-lg-2 col-sm-4">
          <li class="category__item">
            <h4 class="category__heading">Products</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Cases</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Cooling</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Motherboards</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Lighting</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Accessories</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Power</a>
          </li>
        </ul>
        <ul class="category col-lg-2 col-sm-4">
          <li class="category__item">
            <h4 class="category__heading">How to</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Guides</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Blog</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Build Galleries</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Join Team NZXT</a>
          </li>
        </ul>
        <ul class="category col-lg-2 col-sm-4">
          <li class="category__item">
            <h4 class="category__heading">Contact</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Contact Us</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Customer Service</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Create a Ticket</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Company</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Founder Q&A</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Carrers</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">News</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">AM4 Bracket</a>
          </li>
        </ul>
        <ul class="category col-lg-2 col-sm-4">
          <li class="category__item">
            <h4 class="category__heading">Store</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Find a Retailer</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Warranty</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Shipping & Deliveries</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Returns & Exchanges</a>
          </li>

          <li class="category__item mt-5">
            <h4 class="category__heading">Misc</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Log In</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--purple">Sign Up</a>
          </li>
        </ul>
        <ul class="category col-lg-2 col-sm-4">
          <li class="category__item">
            <h4 class="category__heading">PC Monitoring</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--blue">CAM</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--blue">Support</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--blue">Give Feedback</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--blue">Change Log</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--blue">Cam Powered Products</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--blue">Download</a>
          </li>
        </ul>

        <ul class="category col-lg-2 col-sm-4">
          <li class="category__item">
            <h4 class="category__heading">BLD Services</h4>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">BLD</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">What is BLD</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Customer Reviews</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Support</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">FAQ</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Customer Support</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Create a ticket</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Warranty</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Shipping & Deliveries</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Returns & Exchanges</a>
          </li>
          <li class="category__item">
            <a href="#" class="category__link--green">Refurbished Builds</a>
          </li>
        </ul>
      </div>
    </div>
    <Contact></Contact>
  </footer>
</template>

<script>
import Contact from "./Contact";
export default {
  name: "footer",
  components: {
    Contact
  }
};
</script>

<style lang="scss">
.footer {
  background: #101010;
}
.categories {
  padding: 7rem 5rem;
  .category {
    list-style: none;
    margin-bottom: 2rem;

    &__heading {
      text-transform: uppercase;
      color: white;
      margin-bottom: 1rem;
    }

    &__item {
      margin-bottom: 3px;
    }

    &__link {
      &--purple {
        color: #bf4cbf;
      }

      &--blue {
        color: #55a1ff;
      }

      &--green {
        color: #3dadad;
      }
    }
  }
}
</style>