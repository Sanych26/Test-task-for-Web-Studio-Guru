<template>
<div class="slider-container" :style="getStyleContainerObject()">
  <div class="slider" :style="getStyleObject()">
    <div class="item" :style="getStyleContainerObject()">
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <div class="diagram"><img src="../../public/images/diagram.png" alt=""></div>
            <img src="../../public/images/lego_aston.jpeg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Speed Champions Aston Martin Valkyrie AMR PRO та Aston</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>1 379 грн</p>
            </div>
            <div class="old-price">1 499 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <div class="diagram"><img src="../../public/images/diagram.png" alt=""></div>
            <img src="../../public/images/lego_technic.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Technic Всюдихід (42139)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>2 575 грн</p>
            </div>
            <div class="old-price">2 799 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_ferrari.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
            </ul>
            <div class="testimonials">1 відгук</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Speed Champions 1970 Ferrari 512 M (76906)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>670 грн</p>
            </div>
            <div class="old-price">729 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_creator.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
            </ul>
            <div class="testimonials">1 відгук</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Creator Дельфін і черепаха 3 в 1 (31128)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>302 грн</p>
            </div>
            <div class="old-price">329 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_classic.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Classic Океан творчих ігор (11018)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>624 грн</p>
            </div>
            <div class="old-price">679 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
    </div>

    <div class="item" :style="getStyleContainerObject()">
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <div class="diagram"><img src="../../public/images/diagram.png" alt=""></div>
            <img src="../../public/images/lego_aston.jpeg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Speed Champions Aston Martin Valkyrie AMR PRO та Aston</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>1 379 грн</p>
            </div>
            <div class="old-price">1 499 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <div class="diagram"><img src="../../public/images/diagram.png" alt=""></div>
            <img src="../../public/images/lego_technic.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Technic Всюдихід (42139)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>2 575 грн</p>
            </div>
            <div class="old-price">2 799 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_ferrari.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
            </ul>
            <div class="testimonials">1 відгук</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Speed Champions 1970 Ferrari 512 M (76906)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>670 грн</p>
            </div>
            <div class="old-price">729 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_creator.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
            </ul>
            <div class="testimonials">1 відгук</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Creator Дельфін і черепаха 3 в 1 (31128)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>302 грн</p>
            </div>
            <div class="old-price">329 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_classic.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Classic Океан творчих ігор (11018)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>624 грн</p>
            </div>
            <div class="old-price">679 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
    </div>

    <div class="item" :style="getStyleContainerObject()">
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <div class="diagram"><img src="../../public/images/diagram.png" alt=""></div>
            <img src="../../public/images/lego_aston.jpeg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Speed Champions Aston Martin Valkyrie AMR PRO та Aston</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>1 379 грн</p>
            </div>
            <div class="old-price">1 499 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <div class="diagram"><img src="../../public/images/diagram.png" alt=""></div>
            <img src="../../public/images/lego_technic.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Technic Всюдихід (42139)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>2 575 грн</p>
            </div>
            <div class="old-price">2 799 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_ferrari.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
            </ul>
            <div class="testimonials">1 відгук</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Speed Champions 1970 Ferrari 512 M (76906)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>670 грн</p>
            </div>
            <div class="old-price">729 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_creator.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
              <li class="active"></li>
            </ul>
            <div class="testimonials">1 відгук</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Creator Дельфін і черепаха 3 в 1 (31128)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>302 грн</p>
            </div>
            <div class="old-price">329 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
      <div class="slide">
        <div class="slide-content">
          <div class="slide-top-cont">
            <div class="status">
              <p>NEW</p>
            </div>
            <div class="to-favourite"><span></span></div>
          </div>
          <div class="slide-main-photo">
            <img src="../../public/images/lego_classic.jpg" alt="">
          </div>
          <div class="rating-cont">
            <ul class="rating">
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
              <li class=""></li>
            </ul>
            <div class="testimonials">0 відгуків</div>
          </div>
          <div class="description"><a href="">Конструктор LEGO Classic Океан творчих ігор (11018)</a></div>
          <div class="price-cont">
            <div class="new-price">
              <img src="../../public/images/like.png" alt="">
              <p>624 грн</p>
            </div>
            <div class="old-price">679 грн</div>
          </div>
          <div class="buy-btn-cont">
            <button value="buy"><img src="../../public/images/cart.png" alt="">Купити</button>
          </div>
        </div>
      </div>
    </div>


  </div>
</div>
<ul class="navigator">
  <li @click="prevSlide()" class="lightgrey" :style="prevArrowStyle()">&#10094;</li>
  <li @click="nextSlide()" class="lightgrey" :style="nextArrowStyle()">&#10095;</li>
</ul>
</template>

<script>
export default {
  data() {
    return {
      itemWidth: 0,
      slidesCount: 0,
      activeSlide: 1
    };
  },

  mounted() {
    this.initParams()
  },

  methods: {
    initParams() {
      this.sliderContWidth = document.getElementsByClassName('slide').item(0).offsetWidth + 4;
      this.itemWidth = document.getElementsByClassName('item').item(0).offsetWidth;
      this.slidesCount = document.getElementsByClassName('item').length;
    },

    getStyleContainerObject() {
      let contWidth = this.sliderContWidth * 5;
      return {
        width: contWidth + 'px'
      }
    },

    getStyleObject() {
      let sliderWidth = this.sliderContWidth * 5 * this.slidesCount;
      let width = 0 - ((this.activeSlide - 1) * this.sliderContWidth * 5);
      return {
        transform: 'translateX(' + width + 'px)',
        width: sliderWidth + 'px'
      }
    },

    nextArrowStyle() {
      if (this.activeSlide === this.slidesCount) {
        return {
          color: '#e5e5e5',
        }
      }
    },

    prevArrowStyle() {
      if (this.activeSlide === 1) {
        return {
          color: '#e5e5e5',
        }
      }
    },

    nextSlide() {
      if (this.activeSlide < this.slidesCount) this.activeSlide++;
    },

    prevSlide() {
      if (this.activeSlide > 1) this.activeSlide--;
    },
  },
}
</script>

<style>
.slider-container {
  overflow: hidden;
  position: absolute;
}

.slider {
  display: flex;
  flex-direction: row;
  overflow: hidden;
  transition: all .32s ease;
}

.item {
  display: flex;
  justify-content: center;
}

.slide {
  width: 210px;
  margin: 10px 2px;
  display: inline-block;
  border-radius: 6px;
  border: 1px solid #e8eaed;

}

.slide:hover {
  box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.25);
}

.slide-content {
  width: 92%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

.navigator {
  width: 100%;
  padding: 0;
  margin: 17% auto 0;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.navigator li {
  float: left;
  color: #ec008c;
  position: relative;
  cursor: pointer;
  list-style: none;
  transition: all .32s ease;
}

@media (max-width: 1110px){
  
}

</style>
