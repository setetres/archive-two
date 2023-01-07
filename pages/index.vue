<template>
  <CardMain
    class="rounded-t-lg sm:rounded-tr-none sm:rounded-tl-lg"
    color="group-hover:text-indigo-500"
    description="🎂 v15.0 of my website."
    id="index-against-filet"
    label="2023"
    title="Version Fifteen"
    url="/v15"
  >
    <img src="~assets/images/v15.png" width="2560" height="1440" alt="Version Fifteen Screenshot" />
  </CardMain>
  <CardMain
    class="rounded-t-none sm:rounded-tr-lg"
    color="group-hover:text-indigo-500"
    description="✏️ v14.0 of my website."
    id="index-against-filet"
    label="2022"
    title="Version Fourteen"
    url="/v14"
  >
    <img src="~assets/images/v14.png" width="2560" height="1440" alt="Version Fourteen Screenshot" />
  </CardMain>
  <CardMain
    description="🔑 v13.0 of my website."
    color="group-hover:text-indigo-500"
    label="2021"
    title="Version Thirteen"
    url="/v13"
  >
    <img src="~assets/images/v13.png" width="2560" height="1440" alt="Version Thirteen Screenshot" />
  </CardMain>
  <CardMain
    description="🔲 v12.0 of my website."
    color="group-hover:text-indigo-500"
    label="2020"
    title="Version Twelve"
    url="/v12"
  >
    <img src="~assets/images/v12.png" width="2560" height="1440" alt="Version Twelve Screenshot" />
  </CardMain>
  <CardMain
    description="🌿 v11.0 of my website."
    color="group-hover:text-indigo-500"
    label="2019"
    title="Version Eleven"
    url="/v11"
  >
    <img src="~assets/images/v11.png" width="2560" height="1440" alt="Version Eleven Screenshot" />
  </CardMain>
  <CardMain
    description="🌚 v10.0 of my website."
    color="group-hover:text-indigo-500"
    label="2018"
    title="Version Ten"
    url="/v10"
  >
    <img src="~assets/images/v10.png" width="2560" height="1440" alt="Version Ten Screenshot" />
  </CardMain>
  <CardMain
    description="🎉 v9.0 of my website."
    color="group-hover:text-indigo-500"
    label="2017"
    title="Version Nine"
    url="/v9"
  >
    <img src="~assets/images/v9.png" width="2560" height="1440" alt="Version Nine Screenshot" />
  </CardMain>
  <CardMain
    description="✈️ v8.0 of my website."
    color="group-hover:text-indigo-500"
    label="2016"
    title="Version Eight"
    url="/v8"
  >
    <img src="~assets/images/v8.png" width="2560" height="1440" alt="Version Eight Screenshot" />
  </CardMain>
  <CardMain
    description="💧 v7.0 of my website."
    color="group-hover:text-indigo-500"
    label="2015"
    title="Version Seven"
    url="/v7"
  >
    <img src="~assets/images/v7.png" width="2560" height="1440" alt="Version Seven Screenshot" />
  </CardMain>
  <CardMain
    description="🍔 v6.0 of my website."
    color="group-hover:text-indigo-500"
    label="2014"
    title="Version Six"
    url="/v6"
  >
    <img src="~assets/images/v6.png" width="2560" height="1440" alt="Version Six Screenshot" />
  </CardMain>
  <CardMain
    description="🍕 v5.0 of my website."
    color="group-hover:text-indigo-500"
    label="2013"
    title="Version Five"
    url="/v5"
  >
    <img src="~assets/images/v5.png" width="2560" height="1440" alt="Version Five Screenshot" />
  </CardMain>
  <CardMain
    description="✝️ v4.0 of my website."
    color="group-hover:text-indigo-500"
    label="2012"
    title="Version Four"
    url="/v4"
  >
    <img src="~assets/images/v4.png" width="2560" height="1440" alt="Version Four Screenshot" />
  </CardMain>
  <CardMain
    description="🔋 v3.0 of my website."
    color="group-hover:text-indigo-500"
    label="2011"
    title="Version Three"
    url="/v3"
  >
    <img src="~assets/images/v3.png" width="2560" height="1440" alt="Version Three Screenshot" />
  </CardMain>
  <CardMain
    description="🔋 v2.0 of my website."
    color="group-hover:text-indigo-500"
    label="2010"
    title="Version Two"
    url="/v2"
  >
    <img src="~assets/images/v2.png" width="2560" height="1440" alt="Version Two Screenshot" />
  </CardMain>
  <CardMain
    description="👻 v1997 of my website."
    color="group-hover:text-indigo-500"
    label="2009"
    title="Version 1997"
    url="/1997"
  >
    <img src="~assets/images/1997.png" width="2560" height="1440" alt="Version 1997 Screenshot" />
  </CardMain>
  <CardMain
    description="👻 v1.0 of my website."
    color="group-hover:text-indigo-500"
    label="2008"
    title="Version One"
    url="/v1"
  >
    <img src="~assets/images/v1.png" width="2560" height="1440" alt="Version One Screenshot" />
  </CardMain>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-indigo-500"
    description="🗄️ v1.0 of the archive."
    label="2008-2022"
    title="Archive One"
    url="/archive-one"
  >
    <img src="~assets/images/archive-one.png" width="2560" height="1440" alt="Archive One Screenshot" />
  </CardMain>
  <div class="relative bg-zinc-900 p-6 md:p-12 pattern rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg">
    &nbsp;
  </div>
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
