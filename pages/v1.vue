<template>
  <Bar title="v1" />
  <CardImage class="col-span-2">
    <img src="~assets/images/v1.png" width="2560" height="1440" alt="Version One Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      v1
    </Detail>
    <Detail name="Description">
      👻 v1.0 of my website.
    </Detail>
    <Detail name="Framework">
      HTML
    </Detail>
    <Detail name="Year">
      <Tag>
        2008
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v1"
    url="github.com/setetres/v1"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardExternal
    label="Live"
    title="View Project"
    description="v1.setetres.st"
    url="v1.setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
