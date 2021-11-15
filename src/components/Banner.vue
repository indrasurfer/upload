<template>
  <section class="banner-one" id="home">
      <img
        src="../assets/images/bannerkiri.png"
        class="banner-one__bg-shape-1"
        alt=""
      />
      <div class="banner-one__bg hero"></div>
      <div class="container">
        <div class="banner-one__video video-popup">
          <i class="fa fa-play"></i>
        </div>
        <div class="banner-one__moc">
          <img
            src="../assets/images/hp.png"
            class="wow fadeInUp"
            data-wow-duration="1500ms"
            alt=""
          />
        </div>
        <div class="row">
          <div class="col-lg-7">
            <div class="banner-one__content">
              <form
                class="banner-one__mc-form mc-form"
                data-url="MAILCHIMP__POPUP__FORM__URL"
              >
                <input
                  type="text"
                  name="email"
                  placeholder="Email address"
                /><button type="submit" class="thm-btn banner-one__mc-btn">
                  <span>Free Trial</span>
                </button>
              </form>
              <div class="mc-form__response"></div>
              <h3>
                Manage Your <br />
                Project with <br />
                Application
              </h3>
              <p>
                Nulla facilisi. Proin felis neque, suscipit egestas erat a
                <br />
                tincidunt finibus magna consectetur lacus.
              </p>
              <a href="#" class="thm-btn banner-one__btn"
                ><span>Discover More</span></a
              >
            </div>
          </div>
        </div>
      </div>
    </section>
</template>
<style lang="css" scoped>
    .hero {
        background-image: url('../assets/images/kanan.jpg');
    }
</style>