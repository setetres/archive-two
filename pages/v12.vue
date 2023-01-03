<template>
  <Bar title="v12" />
  <CardImage class="col-span-2">
    <img src="~assets/images/v12.png" width="2560" height="1440" alt="Version Twelve Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v12
    </Detail>
    <Detail name="Description">
      🔲 v12.0 of my website.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag>
        2020
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v12"
    url="github.com/setetres/v12"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardExternal
    label="Live"
    title="View Project"
    description="v12.setetres.st"
    url="v12.setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
