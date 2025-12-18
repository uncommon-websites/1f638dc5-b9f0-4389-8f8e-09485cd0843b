<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 0;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<div class="fixed top-0 w-full z-50 flex flex-col font-sans">
  <!-- Top Banner -->
  <div class="bg-[#F3F4F6] border-b border-gray-200 py-2 px-4 text-center text-[10px] sm:text-xs font-medium tracking-wide text-gray-900">
    <span class="mr-1">🎉 Beta Access Now Open: Get 3 Months Free + Priority Support</span>
    <a href="#" class="inline-flex items-center hover:underline font-bold ml-1">
      JOIN THE BETA 
      <svg class="w-3 h-3 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
    </a>
  </div>

  <!-- Main Nav -->
  <nav class="bg-white/95 backdrop-blur-sm border-b border-gray-100 transition-all duration-200 {isScrolled ? 'py-3' : 'py-4'}">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="/" class="flex items-center gap-2">
          <svg width="40" height="28" viewBox="0 0 99 69" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M49.9395 68.9999C45.8555 69.0241 42.5253 65.7227 42.5011 61.626L42.4393 51.1255C41.4253 55.5071 39.3315 59.6219 36.2774 63.0626L35.1218 64.3645C32.4059 67.4241 27.7316 67.6959 24.6815 64.9716C21.6314 62.2473 21.3604 57.5584 24.0763 54.4988L25.2319 53.1969C27.0711 51.125 28.1441 48.5152 28.3248 45.7982C25.0118 52.3089 19.2031 57.2407 12.1793 59.4175L10.519 59.932C6.61699 61.1413 2.47648 58.9486 1.27093 55.0344C0.0653884 51.1202 2.25133 46.9668 6.15336 45.7575L7.81368 45.243C26.4368 39.4714 34.6467 0 50.0422 0C65.4378 0 73.4421 39.4714 92.0652 45.243L93.7255 45.7575C97.6276 46.9668 99.8135 51.1202 98.608 55.0344C97.4024 58.9486 93.2619 61.1413 89.3599 59.932L87.6996 59.4175C80.6758 57.2407 74.8671 52.3089 71.5541 45.7982C71.7348 48.5152 72.8078 51.125 74.647 53.1969L75.8026 54.4988C78.5185 57.5584 78.2475 62.2473 75.1974 64.9716C72.1473 67.6959 67.473 67.4241 64.7571 64.3645L63.6015 63.0626C60.5474 59.6219 58.4536 55.5071 57.4396 51.1255L57.3778 61.626C57.3536 65.7227 54.0234 69.0241 49.9395 68.9999Z" fill="black"/>
          </svg>
          <span class="text-3xl font-serif-display font-bold tracking-tighter text-gray-900">Citr</span>
        </a>
        
        <!-- Desktop Links -->
        <div class="hidden md:flex items-center ml-10 space-x-8 text-sm font-medium text-gray-600">
          <a href="#" class="hover:text-gray-900">Features</a>
          <a href="#" class="hover:text-gray-900">Pricing</a>
          <a href="#" class="hover:text-gray-900">Resources</a>
          <a href="#" class="hover:text-gray-900">Beta Access</a>
        </div>
      </div>

      <!-- Right Actions -->
      <div class="flex items-center space-x-4 sm:space-x-6">
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Sign In</a>
        <a href="#" class="inline-flex items-center justify-center px-4 py-2 border border-transparent text-sm font-medium rounded-full text-white bg-black hover:bg-gray-800 transition-colors shadow-sm">
          Join Beta
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </a>
      </div>
    </div>
  </nav>
</div>
