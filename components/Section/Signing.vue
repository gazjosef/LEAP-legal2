<template>
  <section class="section">
    <div class="section-signing | u-container">
      <picture class="section-signing__img">
        <source
          media="(min-width:351px)"
          srcset="@/assets/images/lc-sign-docs-desktop@2x.png"
        />
        <img
          src="@/assets/images/lc-sign-docs-mobile@2x.png"
          alt="Signing Documents Electronically"
          style="width: auto"
        />
      </picture>
      <div class="section-signing__text">
        <h1
          class="heading-primary-300 | u-margin-bottom-small u-text-primary-100"
        >
          Signing Documents Electronically
        </h1>
        <p class="paragraph">
          LawConnect integrates with DocuSign to provide our users with a quick,
          easy and secure way to sign important legal documents online.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionSigning',
}
</script>

<style lang="scss" scoped></style>
