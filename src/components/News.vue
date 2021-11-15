<template>
  <div class="animated slideInLeft side-menu__block">
    <div class="side-menu__block-overlay custom-cursor__overlay">
      <div class="cursor"></div>
      <div class="cursor-follower"></div>
    </div>
    <div class="side-menu__block-inner">
      <div class="side-menu__top justify-content-end">
        <a href="#" class="side-menu__toggler side-menu__close-btn"
          ><img src="" alt=""
        /></a>
      </div>
      <nav class="mobile-nav__container">
        <ul class="main-nav__navigation-box">
          <li><a href="/">Home</a></li>
          <li><a>Features</a></li>
          <li><a>Pricing</a></li>
          <li><a>Team</a></li>
          <li><a>Screens</a></li>
          <li class="dropdown">
            <a>News</a><i class="fa fa-angle-down"></i>
            <ul>
              <li><a href="/blog">News</a></li>
              <li><a href="/blog-post">News Details</a></li>
            </ul>
          </li>
        </ul>
      </nav>
      <div class="side-menu__sep"></div>
      <div class="side-menu__content">
        <p>
          Lorem Ipsum is simply dummy text the printing and setting industry.
          Lorm Ipsum has been the industry's stanard dummy text ever.
        </p>
        <p>
          <a href="mailto:needhelp@apton.com">needhelp@apton.com</a> <br /><a
            href="tel:888-999-0000"
            >888 999 0000</a
          >
        </p>
        <div class="side-menu__social">
          <a href="#"><i class="fab fa-facebook-square"></i></a
          ><a href="#"><i class="fab fa-twitter"></i></a
          ><a href="#"><i class="fab fa-instagram"></i></a
          ><a href="#"><i class="fab fa-pinterest-p"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "News",
  props: {
    msg: String,
  },
};
</script>
