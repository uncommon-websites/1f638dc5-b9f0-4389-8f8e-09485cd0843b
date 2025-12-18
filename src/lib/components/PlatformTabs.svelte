<script>
    // No script logic needed for this static recreation yet
</script>

<section class="py-20 bg-white font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Real ChatGPT Monitoring</span>
        <h2 class="mt-8 text-5xl md:text-7xl font-serif-display text-gray-900 leading-tight">See exactly what <br/> your customers see <br/> in ChatGPT</h2>
    </div>
    
    <!-- Tabbed interface image area -->
    <div class="max-w-7xl mx-auto mt-16 px-4">
        <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm bg-white grid md:grid-cols-12 min-h-[600px]">
             <div class="md:col-span-4 p-8 md:p-12 border-r border-gray-200 flex flex-col justify-center">
                 <h3 class="text-3xl font-serif-display mb-4">Track citations across thousands of queries</h3>
                 <p class="text-gray-600 text-base leading-relaxed mb-8">Monitor your brand visibility in real-time across the topics that matter most. See citation trends, track competitor mentions, and get automated alerts when your visibility changes. All from the actual ChatGPT interface, not API approximations.</p>
                 <div>
                    <button class="text-sm font-bold border-b border-gray-300 pb-0.5 hover:border-gray-900 transition-colors">Learn More -></button>
                 </div>
             </div>
             <div class="md:col-span-8 bg-gray-50 p-8 md:p-12 flex items-center justify-center relative overflow-hidden">
                 <!-- Simplified UI Mockup -->
                 <div class="bg-white shadow-xl rounded-lg w-full h-full border border-gray-200 p-6 relative flex flex-col">
                    <div class="flex gap-2 mb-6 border-b border-gray-100 pb-4">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                        <div class="ml-auto flex gap-2">
                            <div class="h-4 w-32 bg-gray-100 rounded-full"></div>
                        </div>
                    </div>
                    
                    <div class="space-y-6">
                        <!-- Header Stats -->
                        <div class="grid grid-cols-4 gap-4">
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Visibility</div>
                                 <div class="text-xl font-bold text-gray-900">87</div>
                                 <div class="text-[10px] text-green-600 font-bold">↑ 12%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Citations</div>
                                 <div class="text-xl font-bold text-gray-900">342</div>
                                 <div class="text-[10px] text-green-600 font-bold">+28</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Topics</div>
                                 <div class="text-xl font-bold text-gray-900">15</div>
                                 <div class="text-[10px] text-gray-500 font-bold">Active</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Alerts</div>
                                 <div class="text-xl font-bold text-gray-900">5</div>
                                 <div class="text-[10px] text-orange-600 font-bold">New</div>
                             </div>
                        </div>

                        <!-- Data Table -->
                        <div class="border border-gray-100 rounded-lg overflow-hidden">
                            <div class="bg-gray-50 px-4 py-2 border-b border-gray-100 flex text-[10px] font-bold text-gray-500 uppercase tracking-wider">
                                <div class="w-2/5">Topic</div>
                                <div class="w-1/5 text-center">Citations</div>
                                <div class="w-1/5 text-center">Trend</div>
                                <div class="w-1/5 text-right">Status</div>
                            </div>
                            <div class="divide-y divide-gray-50 text-xs">
                                 {#each [
                                     {topic: 'Best CRM software', citations: '24', trend: '↑ 8%', status: 'Leading'},
                                     {topic: 'Project management tools', citations: '18', trend: '↑ 12%', status: 'Growing'},
                                     {topic: 'Marketing automation', citations: '15', trend: '→ 0%', status: 'Stable'},
                                     {topic: 'Customer support software', citations: '12', trend: '↓ 3%', status: 'Monitor'},
                                     {topic: 'Sales enablement tools', citations: '9', trend: '↑ 15%', status: 'Rising'}
                                 ] as item}
                                 <div class="px-4 py-3 flex items-center hover:bg-gray-50 transition-colors">
                                     <div class="w-2/5 font-medium text-gray-900">{item.topic}</div>
                                     <div class="w-1/5 text-center text-gray-600">{item.citations}</div>
                                     <div class="w-1/5 text-center">
                                         <span class="text-[10px] font-bold {item.trend.includes('↑') ? 'text-green-600' : item.trend.includes('↓') ? 'text-red-600' : 'text-gray-500'}">{item.trend}</span>
                                     </div>
                                     <div class="w-1/5 text-right">
                                         <span class="text-[10px] font-bold text-gray-900">{item.status}</span>
                                     </div>
                                 </div>
                                 {/each}
                            </div>
                        </div>
                    </div>
                 </div>
             </div>
        </div>
        
        <!-- Bottom Grid of 3 items -->
        <div class="grid md:grid-cols-3 gap-0 mt-0 border-x border-b border-gray-200 divide-x divide-gray-200 bg-white">
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">1</div>
                <p class="text-xs text-gray-600 leading-relaxed">Monitor the real ChatGPT interface, not API approximations. See exactly what your customers see when they ask ChatGPT.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">2</div>
                <p class="text-xs text-gray-600 leading-relaxed">Track citation patterns across thousands of queries. Get automated alerts when your visibility changes or competitors gain ground.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">3</div>
                <p class="text-xs text-gray-600 leading-relaxed">Access OpenAI's system prompts and model reasoning. Understand why ChatGPT cites certain sources over others.</p>
            </div>
        </div>
    </div>
</section>