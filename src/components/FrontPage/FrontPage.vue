<template>
  <main class="main">
    <AboveTheFold />

    <Logos />

    <infinite-slide-bar
      duration="10s"
      direction="reverse"
      delay="8s"
      style="margin: 50px auto"
    >
      <section class="main__logos-mobile logos">
        <img
          src="../../image/logo__liva.svg"
          alt="liva"
          title="liva"
          class="logos__logo"
          style="margin-left: -20px"
        />
        <img
          src="../../image/logo__kanba.svg"
          alt="Kanba"
          title="Kanba"
          class="logos__logo"
        />
        <img
          src="../../image/logo__amara.svg"
          alt="Amara"
          title="Amara"
          class="logos__logo"
        />
        <img
          src="../../image/logo__aven.svg"
          alt="Aven"
          title="Aven"
          class="logos__logo"
        />
        <img
          src="../../image/logo__hex-lab.svg"
          alt="Hexlab"
          title="Hexlab"
          class="logos__logo"
        />
        <img
          src="../../image/logo__kanba.svg"
          alt="Kanba"
          title="Kanba"
          class="logos__logo"
        />
      </section>
    </infinite-slide-bar>

    <MainArticle />

    <CardsOpportunity />

    <WhyUs />

    <Needs />

    <Rating />

    <SubArticle />

    <Plans />

    <Members />

    <section class="main__members">
      <div class="main__members-group main__members-group--mobile">
        <Swiper/>
      </div>
    </section>
  </main>
</template>

<script>
import AboveTheFold from './AboveTheFold';
import Logos from './Logos';
import MainArticle from './MainArticle';
import CardsOpportunity from './CardsOpportunity';
import WhyUs from './WhyUs';
import Needs from './Needs';
import Rating from './Rating';
import SubArticle from './SubArticle';
import Plans from './Plans';
import Members from './Members';
import Swiper from './Swiper'
import InfiniteSlideBar from "vue-infinite-slide-bar";

export default {
  components: {
    InfiniteSlideBar,
    Swiper,
    AboveTheFold,
    Logos,
    MainArticle,
    CardsOpportunity,
    WhyUs,
    Needs,
    Rating,
    SubArticle,
    Plans,
    Members
  },
};
</script>
