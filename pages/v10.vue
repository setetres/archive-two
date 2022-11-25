<template>
    <Bar title="v10" />
    <CardImage class="sm:col-span-2 p-12">
        <img src="~assets/images/v10.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/v10.png" width="2560" height="1440" alt="" />
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
        <img src="~assets/images/v10.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail>
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
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="v10.setetres.st"
    url="v10.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>