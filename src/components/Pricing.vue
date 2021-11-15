<template>
  <section class="pricing-one" id="pricing">
    <div class="container">
      <div class="block-title text-center">
        <p>Pricing Tables</p>
        <h3>Choose Pricing Plans Which Suits Your Needs</h3>
      </div>
      <ul
        class="list-inline text-center switch-toggler-list"
        role="tablist"
        id="switch-toggle-tab"
      >
        <li class="month active"><a href="#">Monthly</a></li>
        <li>
          <label class="switch on"><span class="slider round"></span></label>
        </li>
        <li class="year"><a href="#">Annualy</a></li>
      </ul>
      <div id="month">
        <div class="row">
          <div class="col-lg-4">
            <div class="pricing-one__single">
              <div class="pricing-one__circle"></div>
              <div class="pricing-one__inner">
                <p>Basic Pack</p>
                <h3>$20.00</h3>
                <ul class="list-unstyled pricing-one__list">
                  <li>Extra features</li>
                  <li>Lifetime free support</li>
                  <li>Upgrate options</li>
                  <li>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"
                  ><span>Choose Plan</span></a
                ><span>No hidden charges!</span>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="pricing-one__single">
              <div class="pricing-one__circle"></div>
              <div class="pricing-one__inner">
                <p>Standard Pack</p>
                <h3>$40.00</h3>
                <ul class="list-unstyled pricing-one__list">
                  <li>Extra features</li>
                  <li>Lifetime free support</li>
                  <li>Upgrate options</li>
                  <li>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"
                  ><span>Choose Plan</span></a
                ><span>No hidden charges!</span>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="pricing-one__single">
              <div class="pricing-one__circle"></div>
              <div class="pricing-one__inner">
                <p>Ultimate Pack</p>
                <h3>$49.00</h3>
                <ul class="list-unstyled pricing-one__list">
                  <li>Extra features</li>
                  <li>Lifetime free support</li>
                  <li>Upgrate options</li>
                  <li>Full access</li>
                </ul>
                <a href="#" class="thm-btn pricing-one__btn"
                  ><span>Choose Plan</span></a
                ><span>No hidden charges!</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Pricing",
  props: {
    msg: String,
  },
};
