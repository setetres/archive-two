<template>
  <Bar title="v2" />
  <CardImage class="col-span-2">
    <img src="~assets/images/v2.png" width="2560" height="1440" alt="Version Two Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v2
    </Detail>
    <Detail name="Description">
      🎯 v2.0 of my website.
    </Detail>
    <Detail name="Framework">
      HTML
    </Detail>
    <Detail name="Year">
      <Tag>
        2010
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v2"
    url="github.com/setetres/v2"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardExternal
    label="Live"
    title="View Project"
    description="v2.setetres.st"
    url="v2.setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
