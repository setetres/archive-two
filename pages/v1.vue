<template>
  <Bar
    id="back"
    title="v1"
    color="hover:text-indigo-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/v1.png" width="2560" height="1440" alt="Version One Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v1
    </Detail>
    <Detail name="Description">
      👻 v1.0 of my website.
    </Detail>
    <Detail name="Framework">
      HTML
    </Detail>
    <Detail name="Year">
      <Tag color="bg-indigo-500">
        2008
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="github.com/setetres/v1"
    external="true"
    id="github-v1"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/v1"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-indigo-500"
    description="v1.setetres.st"
    external="true"
    id="live-v1"
    label="Live"
    title="View Project"
    url="https://v1.setetres.st"
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
