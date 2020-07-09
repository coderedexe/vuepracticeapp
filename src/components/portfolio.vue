<template>
  <section class="page-section bg-light" id="portfolio">
    <div class="container">
      <div class="text-center">
        <h2 class="section-heading text-uppercase">Portfolio</h2>
        <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
      </div>
    </div>

    <div class="row">
      <div class="col-lg-4 col-sm-6 mb-4" v-for="(obj, key) in portfolioJSON" :key="key">
        <div class="portfolio-item">
          <a class="portfolio-link" data-toggle="modal" href="#portfolioModal1">
            <div class="portfolio-hover">
              <div class="portfolio-hover-content">
                <i class="fas fa-plus fa-3x"></i>
              </div>
            </div>
            <img class="img-fluid" src="assets/img/portfolio/01-thumbnail.jpg" alt />
          </a>
          <div class="portfolio-caption">
            <div class="portfolio-caption-heading">{{ obj.caption }}</div>
            <div class="portfolio-caption-subheading text-muted">{{ obj.title }}</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>



<script>
export default {
  name: "portfolio",
  data: () => ({
    portfolioJSON: [
      {
        img: "/example/random.jpg",
        caption: "Initialize",
        title: "Learning"
      },
      {
        img: "/example/random.jpg",
        caption: "Initialize1",
        title: "Learning1"
      },
      {
        img: "/example/random.jpg",
        caption: "Initialize2",
        title: "Learning2"
      },
      {
        img: "/example/random.jpg",
        caption: "Initialize3",
        title: "Learning3"
      }
    ]
  })
};
</script>



<style>
</style>