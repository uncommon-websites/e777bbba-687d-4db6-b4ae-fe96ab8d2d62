<script lang="ts">
    const demoImage = "/generated/image-ocean-research-vessel-with-advanced-moni-1765466534659-1.webp";
</script>

<section id="technology" class="bg-white py-24 px-6 md:px-12 text-black">
    <div class="max-w-[1400px] mx-auto">
        <!-- Text Header -->
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
            <h2 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight">
                Distributed<br />
                High-Resolution<br />
                Coastal Models
            </h2>
            <div class="flex flex-col justify-between">
                <p class="text-lg md:text-xl leading-relaxed text-gray-800 max-w-xl">
                    Our computational infrastructure delivers 50x finer precision than traditional ocean forecasts. Starting with elite sailing teams, we're scaling to 100+ ports to transform maritime operations with unprecedented coastal current accuracy.
                </p>
                <a href="#" class="inline-flex items-center gap-2 mt-8 text-sm font-medium hover:opacity-70 transition-opacity group">
                    <span class="text-xs group-hover:translate-x-1 transition-transform duration-300">›</span>
                    Request a demo
                </a>
            </div>
        </div>

        <!-- Media Content -->
        <div class="relative w-full aspect-video bg-gray-900 overflow-hidden group">
            <img src={demoImage} alt="Ocean research and coastal modeling technology" class="w-full h-full object-cover" />
            
            <!-- Info Overlay -->
            <div class="absolute bottom-8 left-8 flex items-center gap-4 z-10">
                <div class="bg-black/50 backdrop-blur-sm border border-white/20 px-4 py-2 text-white">
                    <span class="text-xs font-mono uppercase tracking-wider">50x Resolution Advantage</span>
                </div>
            </div>
        </div>
        <div class="flex justify-end mt-2">
             <span class="text-[10px] font-mono tracking-wider text-gray-500 uppercase">Precision coastal forecasting for maritime operations</span>
        </div>
    </div>
</section>
