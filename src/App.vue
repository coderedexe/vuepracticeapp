<template>
  <div id="app">
    <!-- Navbar-->
    <navbar1></navbar1>
    <!-- Masthead-->
    <masthead></masthead>
    <!-- Services-->
    <services></services>
    <!-- Portfolio Grid-->
    <portfolio></portfolio>
    <!-- About-->
    <about></about>
    <!-- Team-->
    <team></team>
    <!-- Clients-->
    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-3 col-sm-6 my-3">
            <a href="#!">
              <img class="img-fluid d-block mx-auto" src="assets/img/logos/envato.jpg" alt />
            </a>
          </div>
          <div class="col-md-3 col-sm-6 my-3">
            <a href="#!">
              <img class="img-fluid d-block mx-auto" src="assets/img/logos/designmodo.jpg" alt />
            </a>
          </div>
          <div class="col-md-3 col-sm-6 my-3">
            <a href="#!">
              <img class="img-fluid d-block mx-auto" src="assets/img/logos/themeforest.jpg" alt />
            </a>
          </div>
          <div class="col-md-3 col-sm-6 my-3">
            <a href="#!">
              <img class="img-fluid d-block mx-auto" src="assets/img/logos/creative-market.jpg" alt />
            </a>
          </div>
        </div>
      </div>
    </div>
    <!-- Contact-->
    <contact></contact>
    <!-- Footer-->
    <footer1></footer1>
    <!-- Portfolio Modals-->
    <portfoliomodals></portfoliomodals>
  </div>
</template>

<script>
import portfolio from "./components/portfolio";
import navbar1 from "./components/navbar1";
import services from "./components/services";
import masthead from "./components/masthead";
import about from "./components/about";
import team from "./components/team";
import portfoliomodals from "./components/portfoliomodals";
import footer1 from "./components/footer1";
import contact from "./components/contact";

export default {
  name: "App",
  components: {
    portfolio,
    navbar1,
    services,
    masthead,
    about,
    team,
    portfoliomodals,
    footer1,
    contact
  }
};
</script>

<style>
</style>
