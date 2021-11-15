<template>
  <section class="team-one" id="team">
    <img
      src=""
      class="team-one__bg-shape-1"
      alt=""
    /><img
      src=""
      class="team-one__bg-shape-2"
      alt=""
    />
    <div class="container">
      <div class="block-title text-center">
        <p>Expert People</p>
        <h3>Meet Our Professional Team Members</h3>
      </div>
      <div class="row">
        <div class="col-lg-3 col-md-6 col-sm-12">
          <div class="team-one__single">
            <div class="team-one__circle"></div>
            <div class="team-one__inner">
              <h3>Nathaniel McKenzie</h3>
              <p>App Designer</p>
              <div class="team-one__image">
                <img
                  src="../assets/images/team-1.jpg"
                  alt=""
                />
              </div>
              <div class="team-one__social">
                <a href="#"><i class="fab fa-facebook-square"></i></a
                ><a href="#"><i class="fab fa-twitter"></i></a
                ><a href="#"><i class="fab fa-instagram"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <div class="team-one__single">
            <div class="team-one__circle"></div>
            <div class="team-one__inner">
              <h3>Ronald Parks</h3>
              <p>App Designer</p>
              <div class="team-one__image">
                <img
                  src="../assets/images/team-2.jpg"
                  alt=""
                />
              </div>
              <div class="team-one__social">
                <a href="#"><i class="fab fa-facebook-square"></i></a
                ><a href="#"><i class="fab fa-twitter"></i></a
                ><a href="#"><i class="fab fa-instagram"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <div class="team-one__single">
            <div class="team-one__circle"></div>
            <div class="team-one__inner">
              <h3>Rachel Walker</h3>
              <p>App Designer</p>
              <div class="team-one__image">
                <img
                  src="../assets/images/team-3.jpg"
                  alt=""
                />
              </div>
              <div class="team-one__social">
                <a href="#"><i class="fab fa-facebook-square"></i></a
                ><a href="#"><i class="fab fa-twitter"></i></a
                ><a href="#"><i class="fab fa-instagram"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <div class="team-one__single">
            <div class="team-one__circle"></div>
            <div class="team-one__inner">
              <h3>Willie Castillo</h3>
              <p>App Designer</p>
              <div class="team-one__image">
                <img
                  src="../assets/images/team-4.jpg"
                  alt=""
                />
              </div>
              <div class="team-one__social">
                <a href="#"><i class="fab fa-facebook-square"></i></a
                ><a href="#"><i class="fab fa-twitter"></i></a
                ><a href="#"><i class="fab fa-instagram"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="video-one">
      <div
        class="container-fluid hero" >
        <div
          class="video-one__content wow fadeInLeft"
          data-wow-duration="1500ms"
        >
          <div class="block-title text-left">
            <p>Video Tutorial</p>
            <h3>Watch Now Our Video Tutorial</h3>
          </div>
        </div>
        <a href="#" class="video-one__btn video-popup"
          ><i class="fa fa-play"></i
        ></a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Team",
  props: {
    msg: String,
  },
};
</script>
<style lang="css" scoped>
    .hero {
        background-image: url('../assets/images/kanan.jpg');
    }
</style>
