<script setup>
    import Block from '~/components/Block.vue';

    import TolstText from '~/components/TolstText.vue'

    import krug from '~/components/krug.vue'
</script>

<template>
    <Block>CONTACT US</Block>

    <div class="w-full h-[517px] flex flex-col items-center justify-center gap-4">
        <TolstText class="text-[24px] mt-[32px]">Hello! Thank you for wanting to get in touch with us.</TolstText>
        <p class="mt-[32px] mr-[65px] w-[532px] leading-[22px]">
            This form will help us understand what you're looking for so we can advise 
            you on the options and collaborate with you to create interactive 
            augmented reality filters that reflect your identity professionally
        </p>
    </div>

    
    
    <div class="w-full h-[517px] flex flex-col items-center justify-center gap-4">
        <input
            id="Full-Name"
            v-model="fullName"
            type="text"
            placeholder="Full Name"
            class="w-[608px] h-[65px] border border-black mt-[5px] p-4 resize-none"
        />
        <input
            id="Email-Address"
            v-model="email"
            type="text"
            placeholder="Email Address"
            class="w-[608px] h-[65px] border border-black mt-[5px] p-4 resize-none"
        />
        <textarea
            id="Message"
            v-model="message"
            placeholder="Message"
            class="w-[608px] h-[142px] border border-black mt-[5px] p-4 resize-none"
        ></textarea>
        <div class="w-[608px] h-[65px] mt-[5px] border border-black flex">
            <input
                id="What-type-of-filter-did-you-choose"
                v-model="filterType"
                type="text"
                placeholder="What type of filter did you choose?"
                class="w-full h-[60px] p-4 resize-none"
            />
            <NuxtLink to="#" class="w-[64px] h-full flex items-center justify-center">∇</NuxtLink>
        </div>
        <h1 class="w-[608px] mt-[5px] text-[18px]">The Filter woulb be for:</h1>
        <div class="w-[608px] h-[65px] mt-[5px] border border-black flex">
            <input
                id="Personal-Use/Business"
                v-model="usageType"
                type="text"
                placeholder="Personal Use / Business"
                class="w-full h-[60px] p-4 resize-none"
            />
            <NuxtLink to="#" class="w-[64px] h-full flex items-center justify-center">∇</NuxtLink>
        </div>
    </div>
    <div class="w-full h-[708px] flex flex-col items-center justify-center">
        <TolstText class="text-[48px]">FOLLOW OUR SOCIAL MEDIA:</TolstText>
        <div class="w-[670px] flex mt-[110px] justify-around">
            <krug></krug>
            <krug></krug>
            <krug></krug>
        </div>
    </div>
</template>

