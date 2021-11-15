<template>
  <div class="contact-one">
    <img src="" class="contact-one__bg-shape-1" alt="" />
    <div class="container">
      <div class="row">
        <div class="col-lg-7">
          <form class="contact-form-validated contact-one__form">
            <div class="block-title text-left">
              <p>Contact Now</p>
              <h3>Have Question? Write a Message</h3>
            </div>
            <div class="row">
              <div class="col-lg-6">
                <input type="text" placeholder="Name" name="name" />
              </div>
              <div class="col-lg-6">
                <input type="text" placeholder="Email Address" name="email" />
              </div>
              <div class="col-lg-6">
                <input type="text" placeholder="Subject" name="subject" />
              </div>
              <div class="col-lg-6">
                <input type="text" placeholder="Phone Number" name="phone" />
              </div>
              <div class="col-lg-12">
                <textarea placeholder="Write Message" name="message"></textarea>
              </div>
              <div class="col-lg-12 text-left">
                <button type="submit" class="thm-btn contact-one__btn">
                  <span>Send Message</span>
                </button>
              </div>
            </div>
          </form>
          <div class="result"></div>
        </div>
        <div class="col-lg-5 d-flex wow fadeInRight" data-wow-duration="1500ms">
          <div class="my-auto">
            <div class="contact-one__image">
              <img src="../assets/images/contact.jpg" width="500px" height="500px" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  <br>
    <div class="cta-three">
      <img src="" class="cta-three__bg-1" alt="" />
      <div class="text-center container">
        <h3>
          Download our App Today &amp; <br />
          Experience Endless Possibilities
        </h3>
        <p>and get started with a free 1 month trial for your business</p>
        <div class="cta-three__btn-wrap">
          <a href="#" class="cta-three__btn"
            ><i class="fa fa-play"></i><span>Get in</span><b>Google Play</b></a
          ><a href="#" class="cta-three__btn"
            ><i class="fab fa-apple"></i><span>Get in</span
            ><b>Apple Store</b></a
          >
        </div>
      </div>
    </div>
    <div>
      <section class="mailchimp-one">
        <div class="container wow fadeInUp">
          <div class="inner-container">
            <div class="mailchimp-one__icon">
              <i class="apton-icon-mail"></i>
            </div>
            <form action="#" class="mailchimp-one__form">
              <input
                type="text"
                placeholder="Enter your email address"
                name="email"
              /><button class="thm-btn mailchimp-one__btn" type="submit">
                <span>Register Now</span>
              </button>
            </form>
          </div>
        </div>
      </section>
      <footer class="site-footer">
        <div class="site-footer__upper">
          <div class="container">
            <div class="row">
              <div class="col-lg-4">
                <div class="footer-widget footer-widget__about">
                  <a href="index.html"
                    ><img
                      src="../assets/images/logo1.png"
                      width="129"
                      alt=""
                  /></a>
                  <p>
                    Lorem Ipsum is simply dummy text the <br />
                    printing and setting industry. Lorm Ipsum<br />
                    has been the text ever.
                  </p>
                </div>
              </div>
              <div class="col-lg-5">
                <div class="footer-widget__links-wrap">
                  <div class="footer-widget">
                    <h3 class="footer-widget__title">Company</h3>
                    <ul class="list-unstyled footer-widget__links-list">
                      <li><a href="#">About</a></li>
                      <li><a href="#">Our Team</a></li>
                      <li><a href="#">Contact</a></li>
                      <li><a href="#">Services</a></li>
                    </ul>
                  </div>
                  <div class="footer-widget">
                    <h3 class="footer-widget__title">Explore</h3>
                    <ul class="list-unstyled footer-widget__links-list">
                      <li><a href="#">News</a></li>
                      <li><a href="#">Features</a></li>
                      <li><a href="#">Download</a></li>
                      <li><a href="#">Free Trial</a></li>
                    </ul>
                  </div>
                  <div class="footer-widget">
                    <h3 class="footer-widget__title">Links</h3>
                    <ul class="list-unstyled footer-widget__links-list">
                      <li><a href="#">Help</a></li>
                      <li><a href="#">Privacy Policy</a></li>
                      <li><a href="#">Terms of Use</a></li>
                      <li><a href="#">Services</a></li>
                    </ul>
                  </div>
                </div>
              </div>
              <div
                class="
                  col-lg-3
                  d-flex
                  align-items-center
                  justify-content-xl-end
                  justify-content-lg-end
                  justify-content-md-center
                  justify-content-sm-center
                "
              >
                <div class="footer-widget">
                  <div class="footer-widget__social">
                    <a href="#"><i class="fab fa-facebook-square"></i></a
                    ><a href="#"><i class="fab fa-twitter"></i></a
                    ><a href="#"><i class="fab fa-instagram"></i></a
                    ><a href="#"><i class="fab fa-pinterest-p"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="site-footer__bottom">
          <div class="container text-center">
            <p>© copyright 2020 by Layerdrops.com</p>
          </div>
        </div>
      </footer>
    </div>
    <a class="scroll-to-top"><i class="fa fa-angle-up"></i></a>
  </div>


</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

