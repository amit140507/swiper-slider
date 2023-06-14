## Swiper slider

```
var mySwiper = new Swiper('.swiper-container', {
    breakpoints: {
    // when window width is >= 320px
    320: {
      slidesPerView: 1,
     // spaceBetween: 5
    },
    // when window width is >= 480px
    480: {
      slidesPerView: 1,
     // spaceBetween: 5
    },
    640: {
      slidesPerView: 1,
     // spaceBetween: 5
    },
    768: {
     slidesPerView: 2,
      spaceBetween: 0,
//       coverflowEffect: {
//         rotate: 0,
//         stretch: -60,
//         depth: 300,
//         modifier: 1,
//         slideShadows : false,
//         },
    },
        992: {
     slidesPerView: 3,
      spaceBetween: 10,
//       coverflowEffect: {
//         rotate: 0,
//         stretch: -60,
//         depth: 300,
//         modifier: 1,
//         slideShadows : false,
//         },
    },
        1024: {
     slidesPerView: 3,
       spaceBetween: 10,
//       coverflowEffect: {
//         rotate: 0,
//         stretch: 0,
//         depth: 300,
//         modifier: 1,
//         slideShadows : false,
//         },
    },
    // when window width is >= 640px
    1200: {
      slidesPerView: 3,
      spaceBetween: 20,
//       coverflowEffect: {
//         rotate: 0,
//         stretch: 0,
//         depth: 300,
//         modifier: 1,
//         slideShadows : false,
//         },
    },
    1440: {
        slidesPerView: 3,
//          spaceBetween: 50,
        coverflowEffect: {
        rotate: 0,
        stretch: -60,
        depth: 300,
        modifier: 1,
        slideShadows : false,
        },
    }
  },
effect: 'coverflow',
     slideToClickedSlide: true,
        loop:true,
        centeredSlides: true,
        slidesPerView: 3,
        spaceBetween: 50,
	autoplay:true,
        coverflowEffect: {
            rotate: 0,
            stretch: 0,
            depth: 400,
            modifier: 1, // 2,3
            slideShadows : false,
        },
  navigation: {
    prevEl: ".swiper-button-prev",
    nextEl: ".swiper-button-next"
  },
  pagination: {
    el: ".swiper-pagination",
    type: 'bullets',
    clickable: true
  },

});
```
```
 <div class="swiper-container">
         <div class="swiper-wrapper">
            <div class="swiper-slide slider-item">
                  <!--  Insert slides here   -->
            </div>
         </div>
        <div class="swiper-pagination"></div>

        <!-- If we need navigation buttons -->
        <div class="swiper-button-prev"></div>
        <div class="swiper-button-next"></div>
 </div>
```
