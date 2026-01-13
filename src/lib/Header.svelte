<script lang="ts">
  import { onMount } from 'svelte';

  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 50;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<header class="w-full bg-white text-gray-900 sticky top-0 z-50 transition-all duration-300">
  <!-- Top Bar -->
  <div class="border-b border-gray-100 hidden md:block">
    <div class="max-w-[1600px] mx-auto px-6 h-10 flex justify-end items-center gap-6 text-[11px] font-medium tracking-wide text-gray-500 uppercase">
      <a href="#" class="hover:text-black transition-colors">News</a>
      <a href="#" class="hover:text-black transition-colors">Resources</a>
      <a href="#" class="hover:text-black transition-colors">Contact</a>
    </div>
  </div>

  <!-- Main Nav -->
  <div class="border-b border-gray-100">
    <div class="max-w-[1600px] mx-auto px-6 h-20 flex justify-between items-center relative">
      <!-- Logo -->
      <div class="w-48">
        <a href="/" class="flex items-center gap-3 group">
          <div class="w-8 h-8 text-primary-600">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M20.5734 7.55963V11.331H15.9021V10.2568L20.5734 7.55963Z" fill="currentColor"/>
              <path opacity="0.9" fill-rule="evenodd" clip-rule="evenodd" d="M20.5724 7.55968L15.9011 10.2569L12.4567 8.26854V2.87418L20.5724 7.55968Z" fill="currentColor"/>
              <path opacity="0.8" fill-rule="evenodd" clip-rule="evenodd" d="M12.4578 2.87418V8.26854L9.01444 10.2569L4.34314 7.55968L12.4578 2.87418Z" fill="currentColor"/>
              <path opacity="0.7" fill-rule="evenodd" clip-rule="evenodd" d="M9.01353 10.2568V14.2333L4.34225 16.9302V7.55963L9.01353 10.2568Z" fill="currentColor"/>
              <path opacity="0.6" fill-rule="evenodd" clip-rule="evenodd" d="M12.4569 16.2217V21.616L4.34225 16.9303L9.01353 14.2333L12.4569 16.2217Z" fill="currentColor"/>
              <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M20.5724 16.9303L12.4567 21.616V16.2217L15.9011 14.2333L20.5724 16.9303Z" fill="currentColor"/>
              <path opacity="0.4" fill-rule="evenodd" clip-rule="evenodd" d="M20.5734 13.1591V16.9303L15.9021 14.2333V13.1591H20.5734Z" fill="currentColor"/>
            </svg>
          </div>
          <span class="text-xl font-display text-black tracking-tight">Tropical Racing</span>
        </a>
      </div>

      <!-- Center Nav -->
      <nav class="hidden md:flex items-center gap-10 text-[13px] font-medium tracking-wide uppercase">
        <a href="#horses" class="hover:text-gray-600 transition-colors">Horses</a>
        <a href="#ownership" class="hover:text-gray-600 transition-colors">Ownership</a>
        <a href="#about" class="hover:text-gray-600 transition-colors">About</a>
        <a href="#contact" class="hover:text-gray-600 transition-colors">Contact</a>
      </nav>

      <!-- Right CTA -->
      <div class="w-48 flex justify-end items-center">
        <a href="#apply" class="bg-primary-600 text-white px-6 py-2.5 text-xs uppercase tracking-widest hover:bg-primary-700 transition-colors">
          Become a Partner
        </a>
      </div>
    </div>
  </div>
</header>
