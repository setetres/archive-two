<template>
  <Bar title="v15" />
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
      <Tag>
        2023
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v15"
    url="github.com/setetres/v15"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardExternal
    label="Live"
    title="View Project"
    description="setetres.st"
    url="setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
