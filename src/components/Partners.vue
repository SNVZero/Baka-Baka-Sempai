<template>
       <div class="partners">
      <div class="partners__title">
          <span>С нами работают</span>
      </div>

        <div class="partners__descr">
          Десятки компаний доверяют нам самое ценное, что у них есть в интернете – свои сайты. Мы делаем всё,
          чтобы наше сотрудничество было долгим.
        </div>


      <div class="partners__slider-1">
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
      </div>
      <div class="partners__slider-2">
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
          <div class="slider__item">
              <img src="./img/company-1.png" alt="">
          </div>
      </div>
    </div>

</template>
<script>
export default {
    
}
</script>
<style >

.partners {
    overflow: hidden;
    padding-bottom: 50px;

}

.partners__title {
    font-weight: bold;
    font-size: 42px;
    line-height: 51px;
    text-align: center;
    color: #050C33;
    margin: 160px auto 10px;
}

.partners__descr {
    width: 768px;
    max-width: 100%;
    text-align: center;
    margin: 0 auto;
    padding-bottom: 42px;
    font-weight: 500;
    font-size: 16px;
    line-height: 22px;
    text-align: center;
    color: #050C33;
    opacity: 0.7;
}

.partners .slick-track {
    display: flex;
}

.partners .partners__slider-1 {
    padding: 0px 15%;
    overflow: hidden;
}

.partners .partners__slider-2{
    padding: 0px 10%;
    overflow: hidden;
}

.partners .slider__item {
    border: 1px solid #E5E5E5;
    border-radius: 5px;
    margin: 5px;

}
.slider__item img{
    width: 192px;
    height: 100px;
}
.partners .slick-track{

    overflow: hidden;
}

.slick-list{
    margin: 0px;
    overflow: visible;
}
</style>