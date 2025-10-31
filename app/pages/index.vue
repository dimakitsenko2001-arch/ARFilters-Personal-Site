<script setup>
    import Block from '~/components/Block.vue';

    import TolstText from '~/components/TolstText.vue'

    import Polosa from '~/components/Polosa.vue'

    import tablik from '~/components/tablik.vue'
</script>

<template>
    <Block>HOME</Block>

    <tablik>
        <div class="w-[996px] h-[301px] flex">
            <img src="/ico1.png" alt="ico1">
            <div class="w-full h-full">
                <TolstText class="ml-[71px] w-[608px] text-[24px]">Hi, I'm Majo and I create custom Instagram and Facebook Filters!</TolstText>
                <p class="mt-[40px] ml-[71px]">
                    Whether you’re just starting to dip your feet in the world of filtering your photographs or trying to up grade your game at social media, you have come to the right place! <br>
                    <br>
                    Also known as the Augmented Reality (AR) filter, the effect is placed over the picture and videos you take on Facebook and Instagram to give it a pleasant and vibrant look.br <br>
                    <br>
                    Keep scrolling to learn how can we help you!
                </p>
            </div>
        </div>
    </tablik>

    <tablik>
        <div class="w-[996px] h-[335px] flex">
            <div class="w-full h-full">
                <TolstText class="w-[608px] mt-[60px] text-[48px]">WHY?</TolstText>
                <p class="w-[568px] mt-[22px] text-[18px]">
                Instagram and Facebook filters, without a doubt, add a creative touch to your stories, surprising and enchanting your followers. But they are also an excellent tool for brand positioning and establishing yourself on social media.
                </p>
            </div>
            <Polosa></Polosa>
        </div>
    </tablik>

    <tablik>
        <div class="w-[996px] h-[335px] flex">
            <Polosa></Polosa>
            <div class="w-full h-full">
                <TolstText class="ml-auto w-[568px] mt-[60px] text-[48px]">Marketing AR DATA</TolstText>
                <p class="ml-auto w-[568px] mt-[22px] text-[18px]">
                Augmented Reality experiences have a 94% higher conversion rate. Users connect 30% more with a brand through AR Advertising. 3 out of 4 users would pay more for a product if they see it in a Virtual 
                Try-On. (According to the latest study by Deloitte & Snap Inc.)
                </p>
            </div>
        </div>
    </tablik>

    <div class="w-full h-[147px] flex justify-center">
        <TolstText class="text-[24px]">Know our options</TolstText>
    </div>

    <div class="w-full h-[410px] bg-[#C4C4C4] flex justify-center items-center flex-col">
        <TolstText class="text-[48px] text-[#000000] mb-[40px]">OUR CLIENTS SAY</TolstText>
        <img class="w-[132px] h-[139px]" src="/ico2.png" alt="ico">
        <p class="mt-[27px]">“Awesome job, it boosted my reach”</p>
    </div>
</template>






