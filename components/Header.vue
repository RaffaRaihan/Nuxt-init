<template>
    <header class="mt-[40px] mb-[70px] px-[100px] w-[1440px] flex justify-between items-center text-center font-space">
        <div class="logo w-[219.54px] py-[10px]">
            <NuxtLink><img src="assets/vectors/logo.svg" alt="logo"></NuxtLink>
        </div>
        <div class="menu text-center items-center">
            <NuxtLink href="#" class="m-4">About Us</NuxtLink>
            <NuxtLink href="#" class="m-4">Services</NuxtLink>
            <NuxtLink href="#" class="m-4">Use Cases</NuxtLink>
            <NuxtLink href="#" class="m-4">Pricing</NuxtLink>
            <NuxtLink href="#" class="m-4">Blog</NuxtLink>
            <ButtonNav />
        </div>
    </header>
</template>