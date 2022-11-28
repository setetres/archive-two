<template>
    <Bar title="v13" />
    <CardImage class="col-span-2 p-12">
        <img src="~assets/images/v13.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/v13.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardText>
        <HeadingSans>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSans>
        <HeadingSerif class="text-5xl">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSerif>
    </CardText>
    <CardImage class="col-span-2 p-12">
        <img src="~assets/images/v13.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail class="col-span-2">
        <Detail name="Project">
            v13
        </Detail>
        <Detail name="Description">
            🔑 v13.0 of my website.
        </Detail>
        <Detail name="Framework">
            Vue / NuxtJS
        </Detail>
        <Detail name="Year">
            <Tag>
                2021
            </Tag>
        </Detail>
    </CardDetail>
    <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v13"
    url="github.com/setetres/v13"
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="v13.setetres.st"
    url="v13.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>