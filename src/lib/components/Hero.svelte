<script>
    // Hero Component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 bg-gray-50 relative overflow-hidden font-sans">
    <!-- Grid Background Pattern -->
    <div class="absolute inset-0 z-0 opacity-[0.4]" 
         style="background-image: linear-gradient(#e5e7eb 1px, transparent 1px), linear-gradient(90deg, #e5e7eb 1px, transparent 1px); background-size: 40px 40px;">
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col items-center text-center">
        
        <!-- Headline -->
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif-display text-gray-900 leading-[1.1] tracking-tight mb-6 max-w-5xl mx-auto">
            Track your brand's <br class="hidden md:block" />
            visibility in 
            <span class="inline-flex items-center align-middle mx-1 md:mx-2 relative -top-1 md:-top-2">
                <svg width="60" height="60" viewBox="0 0 100 100" class="w-10 h-10 md:w-16 md:h-16 text-gray-900" fill="currentColor">
                    <!-- ChatGPT-style icon -->
                    <circle cx="50" cy="50" r="45" fill="none" stroke="currentColor" stroke-width="8"/>
                    <path d="M30 40 L45 55 L70 30" stroke="currentColor" stroke-width="8" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </span>
            ChatGPT
        </h1>

        <!-- Subheadline -->
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
            Monitor how ChatGPT cites your brand in real-time. Track competitors, get alerts, and optimize your AI visibility.
        </p>

        <!-- CTA -->
        <div class="mb-16 flex flex-col sm:flex-row gap-4 items-center">
            <a href="#" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-base font-bold rounded-full text-white bg-black hover:bg-gray-800 transition-all shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
                Join Beta Waitlist
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </a>
            <p class="text-sm text-gray-500">
                <span class="font-bold">Beta testers get:</span> 3 months free + priority support
            </p>
        </div>

        <!-- Dashboard Preview -->
        <div class="w-full max-w-5xl mx-auto rounded-lg overflow-hidden shadow-2xl bg-white border border-gray-200 relative group">
            <!-- Browser Chrome -->
            <div class="bg-gray-100 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
                <div class="flex gap-1.5">
                    <div class="w-3 h-3 rounded-full bg-red-400"></div>
                    <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                    <div class="w-3 h-3 rounded-full bg-green-400"></div>
                </div>
                <div class="flex-1 mx-4">
                    <div class="bg-white rounded px-3 py-1 text-xs text-gray-500 border border-gray-200">
                        app.citr.app/dashboard
                    </div>
                </div>
            </div>

            <!-- Dashboard Content -->
            <div class="p-8 bg-gradient-to-br from-gray-50 to-white min-h-[500px]">
                <!-- Header Stats -->
                <div class="grid grid-cols-3 gap-4 mb-8">
                    <div class="bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
                        <div class="text-xs text-gray-500 uppercase font-bold mb-1">Visibility Score</div>
                        <div class="text-3xl font-bold text-gray-900">87</div>
                        <div class="text-xs text-green-600 font-bold mt-1">↑ 12% this week</div>
                    </div>
                    <div class="bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
                        <div class="text-xs text-gray-500 uppercase font-bold mb-1">Total Citations</div>
                        <div class="text-3xl font-bold text-gray-900">342</div>
                        <div class="text-xs text-green-600 font-bold mt-1">↑ 28 new</div>
                    </div>
                    <div class="bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
                        <div class="text-xs text-gray-500 uppercase font-bold mb-1">Topics Tracked</div>
                        <div class="text-3xl font-bold text-gray-900">15</div>
                        <div class="text-xs text-gray-500 font-bold mt-1">5 active alerts</div>
                    </div>
                </div>

                <!-- Citation Trend Chart Placeholder -->
                <div class="bg-white rounded-lg border border-gray-200 p-6 shadow-sm">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-sm font-bold text-gray-900">Citation Trends</h3>
                        <div class="flex gap-2 text-xs">
                            <span class="px-2 py-1 bg-gray-100 rounded">7D</span>
                            <span class="px-2 py-1 bg-black text-white rounded">30D</span>
                            <span class="px-2 py-1 bg-gray-100 rounded">90D</span>
                        </div>
                    </div>
                    <!-- Simple chart visualization -->
                    <div class="h-48 flex items-end gap-2">
                        {#each [40, 55, 48, 62, 58, 71, 68, 75, 82, 79, 87, 85] as height}
                        <div class="flex-1 bg-black rounded-t transition-all hover:bg-gray-700" style="height: {height}%"></div>
                        {/each}
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
