<template>
  <section>
    <!-- Mobile Header -->
    <div class="wsmobileheader clearfix">
      <a id="wsnavtoggle" class="wsanimated-arrow"><span></span></a>
      <span class="smllogo">
        <nuxt-link class="navbar-brand logo" to="/">
          <span class="logo-img"></span>
        </nuxt-link>
      </span>
      <div class="wssearch clearfix">
        <i class="wsopensearch fas fa-search"></i>
        <i class="wsclosesearch fas fa-times"></i>
        <div class="wssearchform clearfix">
          <form>
            <input type="text" placeholder="Search Here" />
          </form>
        </div>
      </div>
    </div>
    <!-- Mobile Header -->
    <div class="headtoppart clearfix">
      <div class="container">
        <div class="headerwp clearfix">
          <div class="headertopleft clearfix">
            <div class="address clearfix">
              <span
                ><a href="mailto:info@mtaliideals.com"
                  ><i class="far fa-envelope"></i> info@mtaliideals.com</a
                >
              </span>
              <a href="tel:+254724355185"
                ><i class="fas fa-phone"></i> +254724355185</a
              >
            </div>
          </div>
          <div class="headertopright clearfix">
            <nuxt-link class="facebookicon" title="Facebook" to="/"
              ><i class="fab fa-facebook-f"></i>
              <span class="mobiletext02">Facebook</span></nuxt-link
            >
            <nuxt-link class="twittericon" title="Twitter" to="/"
              ><i class="fab fa-twitter"></i>
              <span class="mobiletext02">Twitter</span></nuxt-link
            >
            <nuxt-link class="linkedinicon" title="Linkedin" to="/"
              ><i class="fab fa-linkedin-in"></i>
              <span class="mobiletext02">Linkedin</span></nuxt-link
            >
            <nuxt-link class="googleicon" title="Google" to="/"
              ><i class="fab fa-google"></i>
              <span class="mobiletext02">Google</span></nuxt-link
            >
          </div>
        </div>
      </div>
    </div>
    <!-- desktop menu -->
    <div class="headerfull">
      <div class="container">
        <div class="wsmain clearfix">
          <div class="smllogo">
            <nuxt-link class="navbar-brand logodesk" to="/">
              <span class="logo-imgdesk"></span>
            </nuxt-link>
          </div>
          <nav class="wsmenu clearfix">
            <ul class="wsmenu-list">
              <li aria-haspopup="true">
                <a class="navtext"><span>Deals</span></a>
                <div class="wsshoptabing wtsdepartmentmenu clearfix">
                  <div class="wsshopwp clearfix">
                    <ul class="wstabitem clearfix">
                      <li class="wsshoplink-active">
                        <a href="#"
                          ><i class="fas fa-globe-africa"></i> East Africa
                          Deals</a
                        >
                        <div class="wstitemright clearfix wstitemrightactive">
                          <div class="wstmegamenucoll clearfix">
                            <div class="wstheading clearfix">Kenya</div>
                            <ul class="wstliststy01 clearfix">
                              <li>
                                <a>Camping Deals</a
                                >
                              </li>
                              <li>
                                <a>Lodge Deals</a>
                              </li>
                              <li>
                                <a>Day Trips</a>
                              </li>
                              <li>
                                <a>Flying Deals</a
                                >
                              </li>
                              <li>
                                <a>Mt Kenya Climbing</a
                                >
                              </li>
                              <li>
                                <a>Walking Deals</a>
                              </li>
                              <li>
                                <a>SGR Deals</a>
                              </li>
                              <li>
                                <a>Mombasa Deals</a
                                >
                              </li>
                              <li>
                                <a>Nakuru Deals</a>
                              </li>
                              <li>
                                <a>Naivasha Deals</a
                                >
                              </li>
                              <li>
                                <a>Masai Mara Deals</a>
                              </li>
                              <li>
                                <a>Tsavo Deals</a>
                              </li>
                              <li>
                                <a>Laikipia Deals</a>
                              </li>
                              <li>
                                <a>Samburu Deals</a>
                              </li>
                            </ul>
                            <div class="wstheading clearfix">Tanzania</div>
                            <ul class="wstliststy01 clearfix"></ul>
                            <div class="wstheading clearfix">Uganda</div>
                            <ul class="wstliststy01 clearfix"></ul>
                          </div>
                        </div>
                      </li>
                      <li>
                        <a href="#"
                          ><i class="fas fa-globe-africa"></i> Regional Deals</a
                        >
                        <div class="wstitemright clearfix">
                          <div class="wstmegamenucoll clearfix">
                            <div class="wstheading clearfix">South Africa</div>
                            <div class="wstheading clearfix">Zanzibar</div>
                            <div class="wstheading clearfix">Mauritius</div>
                            <div class="wstheading clearfix">Sychelles</div>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </div>
                </div>
              </li>
              <li aria-haspopup="true">
                <nuxt-link to="about" class="navtext"
                  ><span>About us</span></nuxt-link
                >
              </li>
              <li aria-haspopup="true">
                <nuxt-link to="contact" class="navtext"
                  ><span>Contact us</span></nuxt-link
                >
              </li>
              <li aria-haspopup="true">
                <nuxt-link to="faq" class="navtext"><span>FAQ</span></nuxt-link>
              </li>
              <li aria-haspopup="true" class="wssearchbar clearfix">
                <form class="topmenusearch">
                  <input placeholder="Search Deals By Location, Category..." />
                  <button class="btnstyle">
                    <i class="searchicon fas fa-search"></i>
                  </button>
                </form>
              </li>
              <li class="wscarticon clearfix">
                <a href="#"
                  ><i class="fas fa-shopping-basket"></i>
                  <em class="roundpoint">8</em
                  ><span class="hidetxt">Shopping Cart</span></a
                >
              </li>
              <li aria-haspopup="true" class="wsshopmyaccount">
                <a><i class="fas fa-align-justify"></i>Account</a>
                <ul class="sub-menu">
                  <li>
                    <a href="#"><i class="fab fa-black-tie"></i>View Profile</a>
                  </li>
                  <li>
                    <a href="#"><i class="fas fa-heart"></i>My Wishlist</a>
                  </li>
                  <li>
                    <a href="#"><i class="fas fa-bell"></i>Notification</a>
                  </li>
                  <li>
                    <a><i class="fas fa-cog"></i>Settings</a>
                  </li>
                  <li>
                    <a><i class="fas fa-sign-out-alt"></i>Logout</a>
                  </li>
                  <li>
                    <a><i class="fas fa-sign-in-alt"></i>Sign In</a>
                  </li>
                  <li>
                    <a><i class="fas fa-user-plus"></i>Register</a>
                  </li>
                </ul>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
@import url('../assets/css/fade-down.css');
@import url('../assets/css/webslidemenu.css');
@import url('../assets/css/navbar.css');
</style>
