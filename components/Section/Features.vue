<template>
  <section class="| section u-bg-white">
    <div class="container">
      <h1
        class="heading-primary-200 | u-center-text u-margin-bottom-medium u-text-primary-100"
      >
        One Solution Designed to Make Your Firm More Money
      </h1>

      <div class="u-grid u-auto-columns">
        <UICard
          box="box-1"
          image="lc-greater-collab@2x"
          title="Greater Collaboration"
          excerpt="Collaborate on documents with clients, lawyers and other parties with
        LawConnect's Comment and Reply."
        />
        <UICard
          box="box-2"
          image="lc-work-remote@2x"
          title="Work Remotely"
          excerpt="You can sign in to LawConnect and view, collaborate and share your documents from anywhere."
        />
        <UICard
          box="box-1"
          image="lc-safe-docs@2x"
          title="Safe Documents"
          excerpt="LawConnect stores its data on servers provided by Amazon Web Services and is safer than email."
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionFeatures',
}
</script>

<style lang="scss" scoped>
.section-features {
}
</style>
