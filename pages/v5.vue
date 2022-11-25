<template>
    <Bar title="v5" />
    <CardImage class="sm:col-span-2 p-12">
        <img src="~assets/images/v5.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/v5.png" width="2560" height="1440" alt="" />
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
        <img src="~assets/images/v5.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail>
        <Detail name="Project">
            v5
        </Detail>
        <Detail name="Description">
            🍕 v5.0 of my website.
        </Detail>
        <Detail name="Framework">
            Vue / NuxtJS
        </Detail>
        <Detail name="Year">
            <Tag>
                2013
            </Tag>
        </Detail>
    </CardDetail>
    <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v5"
    url="github.com/setetres/v5"
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="v5.setetres.st"
    url="v5.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>