<template>
    <Bar title="archive-v1" />
    <CardImage class="sm:col-span-2 p-12">
        <img src="~assets/images/archive-v1.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/archive-v1.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardText>
        <HeadingSans>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSans>
        <HeadingSerif class="text-5xl">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSerif>
    </CardText>
    <CardImage class="sm:col-span-2 p-12">
        <img src="~assets/images/archive-v1.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail>
        <Detail name="Project">
            archive-v1
        </Detail>
        <Detail name="Description">
            🟣 v1 of the Archive of my website.
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
    description="github.com/setetres/archive-v1"
    url="github.com/setetres/archive-v1"
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="archive-v1.setetres.st"
    url="archive-v1.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>