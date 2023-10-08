<template>
  <div class="offer" id="oferta">
    <div class="wrapper">
      <div class="title-wrapper">
        <div class="heading" data-aos="fade-in">
          Nasza oferta
        </div>
      </div>
      <div class="cards">
        <div class="card" v-for="(offer, index) in offerList">
          <div class="card-photo" data-aos="fade-in" :data-aos-delay="isMobile ? 100 : index * 100">
            <img :alt="offer.title" :src="`/oferta/${offer.photo}`" />
          </div>
          <div class=" card-content">
            <div class="card-title">
              <span>
                {{ offer.title }}
              </span>
              <span v-if="offer.subtitle">
                {{ offer.subtitle }}
              </span>
            </div>
            <div class="cardlink" v-if="offer.link">
              <Link label="więcej" :link="offer.link" variant="white" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import offerList from '../config/offer.js'

export default {
  name: 'Offer',
  data() {
    return {
      offerList: offerList,
      isMobile: window.innerWidth <= 1200,

    }
  },
}
</script>
