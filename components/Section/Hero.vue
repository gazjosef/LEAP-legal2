<template>
  <section class="section section-hero | u-bg-gradient">
    <!-- HEADER -->
    <LayoutHeader />
    <!-- HERO SECTION -->
    <div class="container">
      <div class="hero">
        <picture class="hero__img">
          <source
            media="(min-width:351px)"
            srcset="../../assets/images/lc-hero-desktop@2x.png"
          />
          <img
            src="../../assets/images/lc-hero-mobile@2x.png"
            alt="Signing Documents Electronically"
            style="width: auto"
          />
        </picture>
        <div class="hero__text">
          <h1 class="heading-primary-100 | u-margin-bottom-small u-text-white">
            The place to work with your lawyer
          </h1>
          <p class="paragraph-100 | u-text-white">
            Your lawyer uses LawConnect to share information with you about your
            legal case in a private, convenient and secure way.
          </p>
          <button class="button">
            <a href="#">Create Free Account</a>
          </button>
          <UIButton />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionHero',
}
</script>

<style lang="scss" scoped>
@use '../../assets/css/abstract/breakpoints.scss';
.section-hero {
  height: 65rem;
  z-index: 0;
  padding-top: 8rem;
  overflow: hidden;

  position: relative;

  // @include respond(desktop) {
  //   padding: 10rem 4rem 4rem 4rem;
  // }

  .hero {
    display: grid;
    grid-template-rows: repeat(2, auto);
    grid-gap: 2rem;

    & > * {
      display: grid;
      place-content: center;
    }

    // @include respond(desktop) {
    //   grid-template-columns: repeat(2, 1fr);

    //   &__text {
    //     margin-right: auto;

    //     grid-column: 1 / span 1;
    //     grid-row: 1 / span 1;
    //   }

    //   &__img {
    //     grid-column: 2 / span 1;
    //     grid-row: 1 / span 1;

    //     position: relative;

    //     &::before {
    //       content: '';
    //       // background-color: rgba($clr-primary-200, 0.2);
    //       -moz-border-radius: 50%;
    //       -webkit-border-radius: 50%;
    //       border-radius: 50%;
    //       height: 35vw;
    //       width: 35vw;

    //       display: inline-block;
    //       position: absolute;
    //       top: 50%;
    //       left: 50%;
    //       z-index: -90;

    //       transform: translate(-50%, -50%);
    //     }

    //     &::after {
    //       content: '';
    //       // background-image: linear-gradient($clr-primary-200, $clr-primary-100);
    //       -moz-border-radius: 50%;
    //       -webkit-border-radius: 50%;
    //       border-radius: 50%;
    //       height: 22vw;
    //       width: 22vw;

    //       display: inline-block;
    //       position: absolute;
    //       top: 50%;
    //       left: 50%;
    //       z-index: -80;

    //       transform: translate(-50%, -50%);
    //     }
    //   }
    // }
  }
}
</style>
