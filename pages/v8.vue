<template>
  <Bar
    id="back"
    title="v8"
    color="hover:text-indigo-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/v8.png" width="2560" height="1440" alt="Version Eight Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v8
    </Detail>
    <Detail name="Description">
      ✈️ v8.0 of my website.
    </Detail>
    <Detail name="Framework">
      HTML
    </Detail>
    <Detail name="Year">
      <Tag color="bg-indigo-500">
        2016
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v8"
    url="github.com/setetres/v8"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardMain
    label="Live"
    title="View Project"
    description="v8.setetres.st"
    url="v8.setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
<script>
  export default {
    mounted() {
      this.$nextTick(() => {
      })
    },
    beforeRouteLeave(to, from, next) {
      setTimeout(function() {
        next()
      }, 173)
    }
  }
</script>
