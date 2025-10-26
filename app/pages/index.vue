<script setup>
    import Block from '~/components/Block.vue';

    import TolstText from '~/components/TolstText.vue'

    import Polosa from '~/components/Polosa.vue'
</script>

<template>
    <Block>головна</Block>

    <div class="w-full h-[526px] flex items-center justify-center">
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
    </div>

    <div class="w-full h-[526px] flex items-center justify-center">
        <div class="w-[996px] h-[335px] flex">
            <div class="w-full h-full">
                <TolstText class="w-[608px] mt-[60px] text-[48px]">WHY?</TolstText>
                <p class="w-[568px] mt-[22px] text-[18px]">
                Instagram and Facebook filters, without a doubt, add a creative touch to your stories, surprising and enchanting your followers. But they are also an excellent tool for brand positioning and establishing yourself on social media.
                </p>
            </div>
            <Polosa class="w-[171px] h-full bg-[#C4C4C4]"></Polosa>
        </div>
    </div>

    <div class="w-full h-[526px] flex items-center justify-center">
        <div class="w-[996px] h-[335px] flex">
            <Polosa class="w-[171px] h-full bg-[#C4C4C4]"></Polosa>
            <div class="w-full h-full">
                <TolstText class="w-[608px] mt-[60px] ml-[180px] text-[48px]">Marketing AR DATA</TolstText>
                <p class="w-[568px] mt-[22px] ml-[180px] text-[18px]">
                Augmented Reality experiences have a 94% higher conversion rate. Users connect 30% more with a brand through AR Advertising. 3 out of 4 users would pay more for a product if they see it in a Virtual 
                Try-On. (According to the latest study by Deloitte & Snap Inc.)
                </p>
            </div>
        </div>
    </div>

    <div class="w-full h-[147px] flex justify-center">
        <TolstText class="text-[24px]">Know our options</TolstText>
    </div>
</template>
