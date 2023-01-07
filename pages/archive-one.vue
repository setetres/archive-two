<template>
  <Bar
    id="back"
    title="archive-one"
    color="hover:text-indigo-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/archive-one.png" width="2560" height="1440" alt="Archive One Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      Archive One
    </Detail>
    <Detail name="Description">
      🗄️ v1.0 of the archive.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag color="bg-indigo-500">
        2008-2022
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="github.com/setetres/archive-one"
    external="true"
    id="github-archive-one"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/archive-one"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-indigo-500"
    description="archive-one.setetres.st"
    external="true"
    id="live-archive-one"
    label="Live"
    title="View Project"
    url="https://archive-one.setetres.st"
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
