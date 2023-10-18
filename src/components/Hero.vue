<template>
    <div class="mx-32 relative h-[calc(100%-120px)]">
        <!-- <div class="sun absolute">
            <img src="../assets/images/sun-in-main-page.png" alt="">
        </div> -->
        <div class="main-title-box flex flex-col items-center justify-center text-center h-full">
            <div class="flex justify-center items-center gap-2">
                <div class="">
                    <img src="../assets/icons/map-pin-alt.png" alt="">
                </div>
                <p class="text-[20px]">Samarkand, Uzbekistan</p>
            </div>
            <div>
                <h1 class="text-[80px]">Registan Square</h1>
            </div>
            <div class="text-[20px] leading-[130%] w-[800px]">
                <p>Stunning showcase of Islamic architecture in Samarkand, Uzbekistan, with three ornate madrasas adorned in blue tiles and calligraphic inscriptions, dating back to the 15th century.</p>
            </div>
            <div class="flex items-center justify-center gap-[4px] ps-[32px] pr-[28px] py-[12px] bg-[#E54545] rounded-[8px] mt-[30px]">
                <button>Explore</button>
                <div>
                    <img src="../assets/icons/arrow-sm-right.svg" alt="">
                </div>
            </div>
        </div>
        <div class="scroll absolute right-0 top-[50%]">
            <div>
                <p>01</p>
            </div>
            <div>
                <span></span>
            </div>
            <div>
                <p>02</p>
            </div>
        </div>
        <div class=" bg-[#ffffff1a] countries flex absolute bottom-0 gap-[16px] items-center py-[12px] ps-3 pr-[16px] rounded-[12px] bg-[rgba(255, 255, 255, 0.10)]">
            <div>
                <img src="../assets/images/carusel-image.png" alt="">
            </div>
            <div class="w-[237px]">
                <p>Budapest, Hungery</p>
                <p>Buda Castle</p>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .sun {
        width: 50%;
    }

    .sun img {
        width: 100%;
        height: 100%;
        overflow: hidden;
    }
</style>
