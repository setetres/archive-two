<template>
  <Bar
    id="back"
    title="v14"
    color="hover:text-indigo-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/v14.png" width="2560" height="1440" alt="Version Fourteen Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v14
    </Detail>
    <Detail name="Description">
      ✏️ v14.0 of my website.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag color="bg-indigo-500">
        2022
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="github.com/setetres/v14"
    external="true"
    id="github-v14"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/v14"
  />
  <CardMain
    class="rounded-br-lg pattern"
    color="group-hover:text-indigo-500"
    description="v14.setetres.st"
    external="true"
    id="live-v14"
    label="Live"
    title="View Project"
    url="https://v14.setetres.st"
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
