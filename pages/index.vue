<template>
  <div class="homeWrapper">
    <section class="Banner">
      <div id="homeSlider" class="carousel slide" data-ride="carousel">
        <ul class="carousel-indicators">
          <li data-target="#homeSlider" data-slide-to="0" class="active"></li>
          <li data-target="#homeSlider" data-slide-to="1"></li>
          <li data-target="#homeSlider" data-slide-to="2"></li>
        </ul>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img
              src="~/assets/img/banner.jpg"
              class="d-block w-100"
              alt="..."
            />
          </div>
          <div class="carousel-item">
            <img
              src="~/assets/img/bannertwo.jpg"
              class="d-block w-100"
              alt="..."
            />
          </div>
          <div class="carousel-item">
            <img
              src="~/assets/img/bannerthree.jpg"
              class="d-block w-100"
              alt="..."
            />
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#homeSlider"
          role="button"
          data-slide="prev"
        >
          <span class="slideControls">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span
          ></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#homeSlider"
          role="button"
          data-slide="next"
        >
          <span class="slideControls">
            <span class="carousel-control-next-icon" aria-hidden="true"></span
          ></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </section>
    <section class="dealsSec">
      <div class="container">
        <div class="row">
          <div class="col-12 hotTop">
            <h3 class="catHeads">
              Hot Deals
              <span class="float-right allLink"
                ><a href="">See All <i class="fas fa-arrow-right"></i></a
              ></span>
            </h3>
          </div>
          <div class="col-12 featList">
            <ul class="row row-eq-height featListInn">
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img src="~/assets/img/dubai.jpg" alt="" class="dealImg" />
                  <div class="discountTag text-center">
                    <span class="promoOff">-50%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">Popular</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Dubai Family Tour</h2>
                    <h3><span>From KES 28,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="fas fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Full Board</p>
                  </div>
                </a>
              </li>
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img src="~/assets/img/paris.jpg" alt="" class="dealImg" />
                  <div class="discountTag text-center">
                    <span class="promoOff">-35%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">New</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Paris Tour</h2>
                    <h3><span>From KES 20,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="fas fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Half Board</p>
                  </div>
                </a>
              </li>
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img src="~/assets/img/indian.jpg" alt="" class="dealImg" />
                  <div class="discountTag text-center">
                    <span class="promoOff">-60%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">Best Value</span>
                  </div>
                  <div class="dealInfo">
                    <h2>South Indian Tour</h2>
                    <h3><span>From KES 20,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="fas fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Varies</p>
                  </div>
                </a>
              </li>
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img src="~/assets/img/rome.jpg" alt="" class="dealImg" />
                  <div class="discountTag">
                    <span class="promoOff">-48%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">New</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Rome,Italy</h2>
                    <h3><span>From KES 30,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="far fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Bed & Breakfast</p>
                  </div>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <section class="adsSect">
      <div class="container">
        <ul class="row row-eq-height adsHolder">
          <li class="col-6 adCont">
            <a href=""
              ><img src="~/assets/img/adone.png" alt="" class="img-fluid"
            /></a>
          </li>
          <li class="col-6 adCont">
            <a href=""
              ><img src="~/assets/img/adtwo.png" alt="" class="img-fluid"
            /></a>
          </li>
        </ul>
      </div>
    </section>
    <section class="dealsSec">
      <div class="container">
        <div class="row">
          <div class="col-12 domesticTop">
            <h3 class="catHeads">
              Latest Deals
              <span class="float-right allLink"
                ><a href="">See All <i class="fas fa-arrow-right"></i></a
              ></span>
            </h3>
          </div>
          <div class="col-12 featList">
            <ul class="row featListInn row-eq-height">
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img src="~/assets/img/mombasa.jpg" alt="" class="dealImg" />
                  <div class="discountTag text-center">
                    <span class="promoOff">-50%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">Popular</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Mombasa</h2>
                    <h3><span>From KES 28,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="far fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Full Board</p>
                  </div>
                </a>
              </li>
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img
                    src="~/assets/img/maasaimara.jpg"
                    alt=""
                    class="dealImg"
                  />
                  <div class="discountTag text-center">
                    <span class="promoOff">-35%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">New</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Maasai Mara</h2>
                    <h3><span>From KES 20,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="far fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Half Board</p>
                  </div>
                </a>
              </li>
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img
                    src="~/assets/img/naivasha.jpg"
                    alt=""
                    class="dealImg"
                  />
                  <div class="discountTag text-center">
                    <span class="promoOff">-60%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">Best Value</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Naivasha</h2>
                    <h3><span>From KES 20,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="far fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Varies</p>
                  </div>
                </a>
              </li>
              <li class="col-12 col-sm-6 col-md-3 col-lg-3 col-xl-3 dealCont">
                <a href="#" class="dealContInn">
                  <img src="~/assets/img/tsavo.jpg" alt="" class="dealImg" />
                  <div class="discountTag">
                    <span class="promoOff">-48%</span>
                  </div>
                  <div class="dealTag">
                    <span class="dealTagCont">New</span>
                  </div>
                  <div class="dealInfo">
                    <h2>Tsavo</h2>
                    <h3><span>From KES 30,000</span> per pax sharing</h3>
                    <p>
                      <i class="far fa-calendar-alt"></i> 07 May 2019 - 09 May
                      2019
                    </p>
                    <p>
                      <i class="fas fa-sun"></i> 2 days
                      <i class="far fa-moon"></i> 3 nights
                    </p>
                    <p><i class="fas fa-hotel"></i> Bed & Breakfast</p>
                  </div>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<style>
.homeWrapper {
  background-image: url('~assets/img/adsbg.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
.carousel-item.active,
.carousel-item-next,
.carousel-item-prev {
  display: block;
}

.slideControls {
  width: 35px;
  height: 35px;
  border-radius: 50%;
  padding: 7px;
  background-color: #000000;
}
.dealsSec {
  background: #d7d7e2;
  padding: 30px 15px;
}
.hotTop {
  min-height: 40px;
  border-radius: 12px 12px 0px 0px;
  padding: 12px 15px;
  background-color: #ec1940;
}
.catHeads {
  color: #ffffff;
  font-size: 20px;
  font-family: 'Montserrat', sans-serif;
  font-weight: 500;
  margin-bottom: 0px;
}
.allLink a {
  color: #ffffff;
  font-size: 16px;
}
.featList {
  background: #ffffff;
  min-height: 200px;
  padding: 30px 15px 15px;
  border-radius: 0px 0px 12px 12px;
}
.featListInn {
  -webkit-padding-start: 0px;
  -moz-padding-start: 0px;
  -o-padding-start: 0px;
  margin-bottom: 0px;
}
.dealCont {
  list-style: none;
  margin-bottom: 30px;
}
.dealImg {
  width: 100%;
}
.discountTag {
  border-style: solid;
  border-width: 60px 60px 0 0;
  border-color: #ec1940 transparent transparent;
  position: absolute;
  top: 0;
  z-index: 1;
}
.promoOff {
  font-family: 'Montserrat';
  font-size: 14px;
  font-weight: 600;
  color: #ffffff;
  line-height: normal;
  transform: rotate(-45deg);
  -webkit-transform: rotate(-45deg);
  -moz-transform: rotate(-45deg);
  -o-transform: rotate(-45deg);
  position: absolute;
  top: -46px;
  left: 3px;
}
.dealTag {
  position: absolute;
  min-width: 55px;
  top: 10px;
  right: 25px;
  background-color: #86c43f;
  text-align: center;
  color: #fff;
  padding-top: 3px;
  padding-bottom: 3px;
}
.dealTagCont {
  font-family: 'Montserrat';
  font-size: 14px;
  font-weight: 600;
  color: #ffffff;
  padding-left: 10px;
  padding-right: 10px;
}
.dealInfo {
  padding: 15px;
  background: #f5f5f5;
}
.dealContInn:hover {
  text-decoration: none;
}
.dealInfo h2 {
  color: #070707;
  font-size: 16px;
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
}
.dealInfo h3 {
  color: #000000;
  font-size: 12px;
  font-family: 'Montserrat', sans-serif;
  font-weight: 600;
  line-height: 26px;
}
.dealInfo h3 span {
  background-color: #ec1940;
  color: #fff;
  border-radius: 5px;
  padding: 3px;
}
.dealInfo p {
  color: #000000;
  font-size: 14px;
  font-family: 'Montserrat', sans-serif;
  line-height: 10px;
}
.adsSect {
  background-color: transparent !important;
  min-height: 150px;
  padding: 50px 15px;
}
.adsHolder {
  -webkit-padding-start: 0px;
  -moz-padding-start: 0px;
  -o-padding-start: 0px;
  margin-bottom: 0px;
}
.adCont {
  list-style: none;
}
.domesticTop {
  min-height: 40px;
  border-radius: 12px 12px 0px 0px;
  padding: 12px 15px;
  background-color: #86c440;
}
</style>
