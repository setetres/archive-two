<template>
  <Bar
    id="back"
    title="v15"
    color="hover:text-indigo-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/v15.png" width="2560" height="1440" alt="Version Fifteen Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v15
    </Detail>
    <Detail name="Description">
      🎂 v15.0 of my website.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag color="bg-indigo-500">
        2023
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="github.com/setetres/v15"
    external="true"
    id="github-v15"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/v15"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-indigo-500"
    description="setetres.st"
    external="true"
    id="live-v15"
    label="Live"
    title="View Project"
    url="https://setetres.st"
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
