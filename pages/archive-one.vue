<template>
  <Bar title="archive-v1" />
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
      <Tag>
        2008-2022
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/archive-one"
    url="github.com/setetres/archive-one"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
  />
  <CardExternal
    label="Live"
    title="View Project"
    description="archive-one.setetres.st"
    url="archive-one.setetres.st"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
