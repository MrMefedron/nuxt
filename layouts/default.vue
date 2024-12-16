<template>
    <header class="">
        <div class="h-20 flex align-center justify-between">
            <img class="h-16 w-16 mt-2 ml-2" src="assets\photo_2024-12-15_20-57-58.jpg"/>
            <div class="flex">
                <div class="mr-3 cursor-pointer">
                    <button class="pt-5 ease-in hover:text-sky-700"><b>Wall</b></button>
                </div>
                <div class="ml-3 cursor-pointer">
                    <button class="pt-5 ease-in hover:text-sky-700"><b>My progress</b></button>
                </div>
            </div>
            <div class="flex pt-3 mr-5">
                <div><img class="w-12 h-12 rounded-full border-4 " src="assets\photo_2024-12-15_20-54-12.jpg"/></div>
                <div class="pl-2"><p><H4>Popachlen</H4></p><p><h5 class="text-xs text-slate-400">Баланс: 100 robux</h5></p></div>
            </div>
        </div>
    </header>
    <slot />
</template>