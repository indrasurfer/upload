<template>
  <div class="page-wrapper" id="wrapper">
    <header class="site-header-one stricky site-header-one__fixed-top">
      <div class="container-fluid">
        <div class="site-header-one__logo">
          <a href="index.html"
            ><img src="../assets/images/logo1.png" width="129" alt="" /></a
          ><span class="side-menu__toggler"><i class="fa fa-bars"></i></span>
        </div>
        <div class="main-nav__main-navigation">
          <ul class="main-nav__navigation-box">
            <li><a href="index.html">Home</a></li>
            <li><a>Features</a></li>
            <li><a>Pricing</a></li>
            <li><a>Team</a></li>
            <li><a>Screens</a></li>
            <li class="dropdown">
              <a>News</a><i class="fa fa-angle-down"></i>
              <ul>
                <li><a href="blog">News</a></li>
                <li><a href="blog-post">News Details</a></li>
              </ul>
            </li>
          </ul>
        </div>
        <div class="main-nav__right">
          <a href="#" class="thm-btn main-nav__btn"
            ><span>Download App</span></a
          >
        </div>
      </div>
    </header>
     <Banner/>
  </div>
</template>

<script>
import Banner from "@/components/Banner.vue";
export default {
  name: "Header",
  props: {
    msg: String,
  },
    components: {
    Banner,
  
  },
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->

