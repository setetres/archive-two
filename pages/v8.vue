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
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="github.com/setetres/v8"
    external="true"
    id="github-v8"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/v8"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-indigo-500"
    description="v8.setetres.st"
    external="true"
    id="live-v8"
    label="Live"
    title="View Project"
    url="https://v8.setetres.st"
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
