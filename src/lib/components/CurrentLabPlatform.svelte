<section class="relative bg-[#FFFCF9] py-32 px-6 md:px-12 overflow-hidden min-h-screen flex flex-col justify-between">
    <div class="max-w-[1400px] mx-auto w-full h-full relative z-10 flex flex-col justify-between min-h-[80vh]">
        <!-- Top Info -->
        <div class="flex justify-between items-start w-full relative z-20">
            <div class="flex flex-col">
                <span class="text-[10px] font-mono font-bold tracking-widest text-gray-900 uppercase">Current Lab Platform</span>
                <span class="text-[10px] font-mono font-bold tracking-widest text-[#FF4D00] mt-2 uppercase">Operational 2024</span>
            </div>

            <div class="text-right hidden md:block">
                <div class="grid grid-cols-[auto_auto] gap-x-8 gap-y-1 text-[10px] font-mono text-gray-500 uppercase tracking-widest">
                    <span class="text-gray-400">Resolution:</span> <span class="text-gray-900">50x finer</span>
                    <span class="text-gray-400">Coverage:</span> <span class="text-gray-900">100+ ports</span>
                    <span class="text-gray-400">Model Type:</span> <span class="text-gray-900">Distributed coastal</span>
                    <span class="text-gray-400">Precision:</span> <span class="text-gray-900">Sub-kilometer</span>
                    <span class="text-gray-400">Update Frequency:</span> <span class="text-gray-900">Real-time</span>
                    <span class="text-gray-400">Compute Power:</span> <span class="text-gray-900">HPC cluster</span>
                    <span class="text-gray-400">Data Sources:</span> <span class="text-gray-900">Multi-sensor</span>
                </div>
            </div>
        </div>

        <!-- Center Graphic -->
        <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
            <!-- Large Watermark Text -->
            <h1 class="text-[18vw] font-bold text-[#F0EFEA] tracking-tighter select-none leading-none text-center z-0">
                Current Lab
            </h1>
            
            <!-- Circular Gauge SVG -->
            <div class="absolute inset-0 flex items-center justify-center z-10">
                <svg viewBox="0 0 200 200" class="w-[90vw] h-[90vw] md:w-[45vw] md:h-[45vw]">
                    <!-- Ticks -->
                    {#each Array(180) as _, i}
                        <line 
                            x1="100" y1="20" 
                            x2="100" y2={i % 10 === 0 ? "28" : "24"} 
                            stroke={i === 0 ? "#FF4D00" : "#E5E5E5"} 
                            stroke-width={i === 0 ? "1" : "0.5"}
                            transform="rotate({i * 2} 100 100)"
                        />
                    {/each}
                    <!-- Top Orange Indicator Line -->
                     <line x1="100" y1="10" x2="100" y2="35" stroke="#FF4D00" stroke-width="1" />
                </svg>
            </div>
        </div>

        <!-- Bottom Info -->
        <div class="w-full relative z-20 mt-auto">
            <h3 class="text-2xl md:text-3xl font-medium max-w-xs mb-8 text-gray-900 leading-tight">
                Distributed high-resolution coastal modeling for maritime certainty
            </h3>
            <a href="#" class="inline-flex items-center gap-2 text-sm font-medium hover:opacity-70 transition-opacity group text-gray-900">
                <span class="text-xs group-hover:translate-x-1 transition-transform duration-300">›</span>
                Learn more
            </a>
        </div>
    </div>
</section>
