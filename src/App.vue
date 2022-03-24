<template>
  <div id="app">
    <div class="main">
    <div id="carouselExampleIndicators" class="carousel slide">
          <!-- Header -->
        <div class="header">
            <div class="header-left">
                <div class="Path"><h2 class="purple-m">M</h2></div>
                <div class="Rectangle"></div>
                <div class="header-left-button"><button class="header-left-btn">Appoinment <i class="fa-solid fa-arrow-right"></i></button> </div>
            </div>
            <div class="header-right">
                <ul>
                    <li><a href="">Home</a><i class="fa-solid fa-angle-down fa-sm"></i></li>
                    <li><a href="">Pages</a><i class="fa-solid fa-angle-down fa-sm"></i></li>
                    <li><a href="">Services</a><i class="fa-solid fa-angle-down fa-sm"></i></li>
                    <li><a href="">Case Studies</a><i class="fa-solid fa-angle-down fa-sm"></i></li>
                    <li><a href="">Elements</a><i class="fa-solid fa-angle-down fa-sm"></i></li>
                    <li><a href="">News</a><i class="fa-solid fa-angle-down fa-sm"></i></li>
                    <i class="fa-solid fa-magnifying-glass"></i>
                </ul>
            </div>
        </div>
                  <!-- Header End -->
        <div class="carousel-indicators">  
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="mid">
                <h1 class="header1">Motero Services</h1>
                <p class="header-p">We design & build brands, campaigns & digital <br> projects for businesses large & small.</p>
                <a href="" class="mid-link">Learn more</a>
              </div>
          </div>
          <div class="carousel-item">
            <img src="images/unsplash_g1Kr4Ozfoac.png" class="d-block w-100 carousel-img" alt="...">
          </div>
          <div class="carousel-item">
            <img src="images/unsplash_g1Kr4Ozfoac.png" class="d-block w-100 carousel-img" alt="...">
          </div>
        </div>
      </div>
      <!-- Slider End -->
      <!-- Pages -->
      <div class="pages">
            <div class="logos">
                <a href=""><img src="images/Logo4.png" alt="" class="logo-p"></a>
                <a href=""><img src="images/Logo3.png" alt="" class="logo-p"></a>                
                <a href=""><img src="images/Logo2.png" alt="" class="logo-p"></a>
                <a href=""><img src="images/Logo1.png" alt="" class="logo-p"></a>
                <a href=""><img src="images/Logo.png" alt=""></a>
            </div>
      </div>
      <!-- Pages End -->
      <!-- Our Services -->
      <div class="services">
        <span class="Our-Services">Our Services</span>
        <div class="services-top">
          <div class="box-s">
            <h3>Design <br> Product Software</h3>
            <img src="/images/Illus.png" alt="">
            <p>We meet customers in set place to discuss the details about needs and demands before proposing a plan.
            </p>
            <a href="">Learn more</a>
          </div>
          <div class="box-s">
            <h3>Design <br> Product Software</h3>
            <img src="/images/Illus1.png" alt="">
            <p>We meet customers in set place to discuss the details about needs and demands before proposing a plan.
            </p>
            <a href="">Learn more</a>
          </div>
          <div class="box-s">
            <h3>Design <br> Product Software</h3>
            <img src="/images/Illus2.png" alt="">
            <p>We meet customers in set place to discuss the details about needs and demands before proposing a plan.
            </p>
            <a href="">Learn more</a>
          </div>
          <div class="box-s">
            <div class="special">
            <h3>Design <br> Product Software</h3>
            <img src="/images/Illus.png" alt="">
            <p>We meet customers in set place to discuss the details about needs and demands before proposing a plan.
            </p>
            <a href="">Learn more</a>
          </div>
            <div class="oval-box"></div>
          </div>
        </div>
        <div class="services-bottom">
          <div class="s-b-left">
          <div class="img-s"><img src="./assets/images/unsplash_gcsNOsPEXfs.png" alt=""></div> 
          <div class="img-s"><img src="./assets/images/unsplash_YDVdprpgHv4.png" alt=""></div>
          </div>
          <div class="s-b-right">
            <div class="text-s">
              <span>60</span>
              <span class="Happly-Client">Happly Client</span>
          </div>
            <div class="text-s"></div>
            <div class="text-s"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
@import './assets/css/main.css';
</style>
