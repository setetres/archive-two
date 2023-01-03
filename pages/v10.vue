<template>
  <Bar title="v10" />
  <CardImage class="col-span-2">
    <img src="~assets/images/v10.png" width="2560" height="1440" alt="Version Ten Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v10
    </Detail>
    <Detail name="Description">
      🌚 v10.0 of my website.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag>
        2018
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v10"
    url="github.com/setetres/v10"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardExternal
    label="Live"
    title="View Project"
    description="v10.setetres.st"
    url="v10.setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
