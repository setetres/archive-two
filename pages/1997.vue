<template>
  <Bar
    id="back"
    title="1997"
    color="hover:text-indigo-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/1997.png" width="2560" height="1440" alt="Version 1997 Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      1997
    </Detail>
    <Detail name="Description">
      🚧 v1997 of my website.
    </Detail>
    <Detail name="Framework">
      HTML
    </Detail>
    <Detail name="Year">
      <Tag color="bg-indigo-500">
        2009
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="github.com/setetres/1997"
    external="true"
    id="github-1997"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/1997"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-indigo-500"
    description="1997.setetres.st"
    external="true"
    id="live-1997"
    label="Live"
    title="View Project"
    url="https://1997.setetres.st"
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
