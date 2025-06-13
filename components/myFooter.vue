<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
    <img src="../assets/footer.png" class="absolute bottom-0 left-1 w-30 opacity-95">
    <div class="abs-br m-6 flex items-center gap-2">
        <div class="text-3 text-left text-slate-400"> <carbon:user-speaker /> Educational Session <carbon:login /> Maximizing Scientific Efficiency <carbon:chat /> {{ $slidev.configs.title }} </div>
    </div>
    <div class="abs-tr mt-8 mr-6 flex items-center gap-2 bg-slate-100 rounded-lg shadow-lg border-1 pl-1 pr-1">
        <div class="text-3 text-left text-slate-400"> <carbon:presentation-file /> <SlideCurrentNo class="text-primary" /> / <SlidesTotal class="text-slate-500" /> </div>
    </div>
    <div class="absolute bottom-3.4 left-32 right-0 flex items-center gap-2 h-1.7 w-full" style="background: #5097a9;"></div>
    <div class="absolute bottom-1.7 left-32 right-0 flex items-center gap-2 h-1.7 w-full" style="background: #8d424d;"></div>
    <div class="absolute bottom-0 left-32 right-0 flex items-center gap-2 h-1.7 w-full bg-black"></div>
    <div class="absolute top-0 left-0 right-0 flex items-center gap-2 h-1.7 w-full bg-black"></div>
    <div class="absolute top-1.7 left-0 right-0 flex items-center gap-2 h-1.7 w-full" style="background: #8d424d;"></div>
    <div class="absolute top-3.4 left-0 right-0 flex items-center gap-2 h-1.7 w-full" style="background: #5097a9;"></div>
</template>
