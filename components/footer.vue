<template class="footSection">
  <section>
    <div class="footerTop">
      <div class="container">
        <div class="row">
          <div class="col-6 col-sm-6 col-md-3 footSecs">
            <h5>Categories</h5>
            <ul class="footLinks">
              <li>Hot Deals</li>
              <li>Latest Deals</li>
              <li>Domestic Deals</li>
              <li>Holiday Packages</li>
            </ul>
          </div>
          <div class="col-6 col-sm-6 col-md-3 footSecs">
            <h5>Quick Links</h5>
            <ul class="footLinks">
              <li>About us</li>
              <li>Contact us</li>
              <li>Terms of use</li>
              <li>Privacy policy</li>
            </ul>
          </div>
          <div class="col-12 col-sm-6 col-md-3 footSecs">
            <h5>We Are Social</h5>
            <ul class="footSocial">
              <li><i class="fab fa-facebook-f"></i></li>
              <li><i class="fab fa-twitter"></i></li>
              <li><i class="fab fa-instagram"></i></li>
              <li><i class="fab fa-linkedin-in"></i></li>
            </ul>
            <h5>Payment Methods:</h5>
            <ul class="payments">
              <li>
                <img src="~/assets/img/mpesa.png" alt="" class="img-fluid" />
              </li>
              <li>
                <img
                  src="~/assets/img/visalogo.png"
                  alt=""
                  class="img-fluid"
                />
              </li>
              <li>
                <img src="~/assets/img/paypal.png" alt="" class="img-fluid" />
              </li>
            </ul>
          </div>
          <div class="col-12 col-sm-6 col-md-3 footSecs">
            <h5>Subscribe to our Newsletter</h5>
            <div class="input-group mt-3 mb-4">
              <input type="email" class="form-control" />
              <div class="input-group-append">
                <button class="btn btn-success" type="submit">
                  <i class="fas fa-paper-plane"></i>
                </button>
              </div>
            </div>
            <h5>Download our App on:</h5>
            <ul class="footDowns">
              <li>
                <img
                  src="~/assets/img/googleplay.png"
                  alt=""
                  class="img-fluid"
                />
              </li>
              <li>
                <img
                  src="~/assets/img/appstore.png"
                  alt=""
                  class="img-fluid"
                />
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footerBtm">
      <div class="container">
        <div class="text-center">
          <p class="copyright">&copy; 2019 Mtalii Deals</p>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.footerTop {
  min-height: 280px;
  padding-top: 50px;
  padding-bottom: 30px;
  background-color: #434343;
}

.footSecs {
  margin-bottom: 30px;
}

.footSecs h5 {
  font-family: 'Montserrat', sans-serif;
  font-weight: 600;
  color: #ffffff;
  font-size: 18px;
  text-decoration: underline;
  margin-bottom: 15px;
}

.footLinks {
  -webkit-padding-start: 0px;
  -moz-padding-start: 0px;
  -o-padding-start: 0px;
}

.footLinks li {
  list-style: none;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  color: #ffffff;
  font-size: 14px;
  line-height: 30px;
}

.footSocial {
  -webkit-padding-start: 0px;
  -moz-padding-start: 0px;
  -o-padding-start: 0px;
  margin-bottom: 30px;
}
.footSocial li {
  list-style: none;
  display: inline-block;
  margin-right: 25px;
  width: 30px;
  height: 30px;
  border: 1px solid #ffffff;
  border-radius: 9px;
  text-align: center;
  color: #ffffff;
  padding-top: 2px;
  margin-bottom: 15px;
}
.payments {
  margin-top: 10px;
  -webkit-padding-start: 0px;
  -moz-padding-start: 0px;
  -o-padding-start: 0px;
  display: grid;
  grid-template-columns: auto auto auto;
  grid-column-gap: 20px;
}
.payments li {
  list-style: none;
}
.footDowns {
  -webkit-padding-start: 0px;
  -moz-padding-start: 0px;
  -o-padding-start: 0px;
  display: grid;
  grid-template-columns: auto auto;
  grid-column-gap: 15px;
}
.footDowns li {
  list-style: none;
}
.footerBtm {
  min-height: 60px;
  background-color: #222324;
  padding-top: 20px;
}

.copyright {
  color: #ffffff;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 15px;
}
</style>
