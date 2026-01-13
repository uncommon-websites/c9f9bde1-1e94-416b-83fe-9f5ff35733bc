<script lang="ts">
    // Images placeholders - horse racing themed
    const heroImage = "https://images.unsplash.com/photo-1568605117036-5fe5e7bab0b7?q=80&w=2560&auto=format&fit=crop";
    const horse1 = "https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?q=80&w=1000&auto=format&fit=crop";
    const horse2 = "https://images.unsplash.com/photo-1551884831-bbf3cdc6469e?q=80&w=1000&auto=format&fit=crop";
    const training = "https://images.unsplash.com/photo-1534279655-c0b8f8d0b6f1?q=80&w=2560&auto=format&fit=crop";
    const stableImage = "https://images.unsplash.com/photo-1598632640487-6ea4a4e8b963?q=80&w=1000&auto=format&fit=crop";
    const horseDetail = "https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?q=80&w=1000&auto=format&fit=crop";
    const trackImage = "https://images.unsplash.com/photo-1568605117036-5fe5e7bab0b7?q=80&w=2560&auto=format&fit=crop";
    const horse3 = "https://images.unsplash.com/photo-1598632640487-6ea4a4e8b963?q=80&w=1000&auto=format&fit=crop";
    const facilityImage = "https://images.unsplash.com/photo-1534279655-c0b8f8d0b6f1?q=80&w=2560&auto=format&fit=crop";
    const raceDay = "https://images.unsplash.com/photo-1568605117036-5fe5e7bab0b7?q=80&w=1000&auto=format&fit=crop";
    const ownerExperience = "https://images.unsplash.com/photo-1551884831-bbf3cdc6469e?q=80&w=1000&auto=format&fit=crop";
    const ctaLeft = "https://images.unsplash.com/photo-1568605117036-5fe5e7bab0b7?q=80&w=2000&auto=format&fit=crop";
    const ctaRight = "https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?q=80&w=2000&auto=format&fit=crop";

</script>

<div class="w-full">
    <!-- Hero Section -->
    <section class="w-full mb-16 md:mb-24 px-4 md:px-6 max-w-[1600px] mx-auto">
        <div class="relative w-full aspect-[16/9] md:aspect-[21/9] overflow-hidden">
            <img src={heroImage} alt="Elite Thoroughbred Racing" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/20 to-transparent"></div>
            <div class="absolute bottom-0 left-0 right-0 p-8 md:p-12 text-white">
                <h1 class="font-display text-4xl md:text-6xl lg:text-7xl mb-4 max-w-4xl">Elite Thoroughbred Ownership, Redefined</h1>
                <p class="text-lg md:text-xl font-light max-w-2xl opacity-90">Experience the thrill of racehorse ownership through transparent partnerships and professional bloodstock management.</p>
            </div>
        </div>
    </section>

    <!-- Intro Section -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-24">
            <div>
                <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-8">A New Standard in Racehorse Ownership</h2>
                <div class="text-gray-600 text-sm leading-relaxed space-y-4 max-w-md font-light">
                    <p>
                        Tropical Racing delivers elite Thoroughbred ownership experiences through aligned co-ownership structures, transparent flat-fee pricing, and professional bloodstock management.
                    </p>
                    <p>
                        We've reimagined racehorse partnerships for the modern enthusiast—eliminating opaque syndicates and surprise costs while maintaining the highest standards of care and performance.
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-y-6 text-[11px] uppercase tracking-wider">
                <div class="text-gray-400">Business Model</div>
                <div class="text-gray-900">Curated Thoroughbred Partnerships</div>

                <div class="text-gray-400">Target Partners</div>
                <div class="text-gray-900">Affluent Racing Enthusiasts</div>

                <div class="text-gray-400">Approach</div>
                <div class="text-gray-900">Transparent & Aligned</div>

                <div class="col-span-2 pt-6 border-t border-gray-100 mt-2">
                    <div class="text-gray-400 mb-1">Key Differentiator</div>
                    <div class="text-gray-900">Flat-fee structure with aligned upside economics</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
            <div class="text-center">
                <div class="w-16 h-16 mx-auto mb-6 flex items-center justify-center bg-primary-50 text-primary-600 rounded-full">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 0 1 0-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178Z" />
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z" />
                    </svg>
                </div>
                <h3 class="font-display text-xl mb-3">Complete Transparency</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">Flat-fee structure with no hidden costs. You know exactly what you're paying, and we share in the upside together.</p>
            </div>
            <div class="text-center">
                <div class="w-16 h-16 mx-auto mb-6 flex items-center justify-center bg-primary-50 text-primary-600 rounded-full">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                    </svg>
                </div>
                <h3 class="font-display text-xl mb-3">Professional Management</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">Expert bloodstock selection and care. Every horse receives world-class training and veterinary attention.</p>
            </div>
            <div class="text-center">
                <div class="w-16 h-16 mx-auto mb-6 flex items-center justify-center bg-primary-50 text-primary-600 rounded-full">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 0 0 3.741-.479 3 3 0 0 0-4.682-2.72m.94 3.198.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0 1 12 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 0 1 6 18.719m12 0a5.971 5.971 0 0 0-.941-3.197m0 0A5.995 5.995 0 0 0 12 12.75a5.995 5.995 0 0 0-5.058 2.772m0 0a3 3 0 0 0-4.681 2.72 8.986 8.986 0 0 0 3.74.477m.94-3.197a5.971 5.971 0 0 0-.94 3.197M15 6.75a3 3 0 1 1-6 0 3 3 0 0 1 6 0Zm6 3a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Zm-13.5 0a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Z" />
                    </svg>
                </div>
                <h3 class="font-display text-xl mb-3">Aligned Interests</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">We succeed when you succeed. Our economics are aligned with yours through shared upside participation.</p>
            </div>
        </div>
    </section>

    <!-- Featured Horse Section -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-start">
            <div class="md:col-span-5 md:col-start-2">
                <img src={horse1} alt="Featured Thoroughbred" class="w-full aspect-[3/4] object-cover mb-4" />
                <p class="text-xs text-gray-400 font-light max-w-xs mt-8 leading-relaxed">
                    Each horse in our portfolio is carefully selected for pedigree, conformation, and racing potential. We partner with leading trainers and bloodstock agents to identify exceptional prospects.
                </p>
            </div>
            <div class="md:col-span-5 md:col-start-8 md:mt-32">
                 <img src={horse2} alt="Thoroughbred portrait" class="w-full aspect-square object-cover" />
            </div>
        </div>
    </section>

    <!-- Full Width Training Image -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <img src={training} alt="Training session" class="w-full aspect-[16/9] md:aspect-[21/9] object-cover" />
    </section>

    <!-- How It Works -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <h2 class="font-display text-3xl md:text-4xl text-center mb-16">How Partnership Works</h2>
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
            <div class="relative">
                <div class="text-6xl font-display text-primary-100 mb-4">01</div>
                <h3 class="text-lg font-bold mb-2">Curated Selection</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">We identify exceptional Thoroughbred prospects through our network of bloodstock experts and trainers.</p>
            </div>
            <div class="relative">
                <div class="text-6xl font-display text-primary-100 mb-4">02</div>
                <h3 class="text-lg font-bold mb-2">Transparent Pricing</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">Flat-fee structure with clear partnership terms. No surprise costs or hidden fees.</p>
            </div>
            <div class="relative">
                <div class="text-6xl font-display text-primary-100 mb-4">03</div>
                <h3 class="text-lg font-bold mb-2">Professional Care</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">World-class training, veterinary care, and race placement managed by experienced professionals.</p>
            </div>
            <div class="relative">
                <div class="text-6xl font-display text-primary-100 mb-4">04</div>
                <h3 class="text-lg font-bold mb-2">Shared Success</h3>
                <p class="text-sm text-gray-600 font-light leading-relaxed">Aligned economics mean we share in the upside. Your success is our success.</p>
            </div>
        </div>
    </section>

    <!-- Image Grid 2 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
                <img src={stableImage} alt="Premium stable facilities" class="w-full aspect-[3/4] object-cover" />
            </div>
            <div class="flex flex-col justify-between">
                <img src={horseDetail} alt="Thoroughbred close-up" class="w-full aspect-[3/4] object-cover mb-8" />
                <div class="max-w-xs ml-auto">
                     <p class="text-xs text-gray-400 font-light leading-relaxed">
                        Every aspect of horse care is managed with meticulous attention to detail. From nutrition and training regimens to veterinary oversight and race strategy, our team ensures each horse receives the support needed to perform at their peak.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Grid 3 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-end">
             <div class="md:col-span-5">
                <img src={horse3} alt="Horse in paddock" class="w-full aspect-[4/5] object-cover" />
            </div>
            <div class="md:col-span-7">
                <img src={trackImage} alt="Race track view" class="w-full aspect-[4/3] object-cover" />
            </div>
        </div>
    </section>

    <!-- Large Facility Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={facilityImage} alt="Training facilities" class="w-full h-[80vh] object-cover" />
    </section>

    <!-- Testimonials Section -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <h2 class="font-display text-3xl md:text-4xl text-center mb-16">What Our Partners Say</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
            <div class="border-l-2 border-primary-600 pl-6">
                <p class="text-gray-700 mb-6 leading-relaxed italic">
                    "After years of frustration with traditional syndicates and their surprise costs, Tropical Racing's transparent approach was refreshing. I finally feel like a true partner, not just a checkbook."
                </p>
                <div class="text-sm">
                    <div class="font-bold">Michael R.</div>
                    <div class="text-gray-500">Partner since 2023</div>
                </div>
            </div>
            <div class="border-l-2 border-primary-600 pl-6">
                <p class="text-gray-700 mb-6 leading-relaxed italic">
                    "The professionalism and care that goes into every aspect of horse management is evident. From bloodstock selection to race day, I trust the Tropical Racing team completely."
                </p>
                <div class="text-sm">
                    <div class="font-bold">Sarah L.</div>
                    <div class="text-gray-500">Partner since 2022</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Grid 4 & Text -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-16 items-start">
            <img src={raceDay} alt="Race day excitement" class="w-full aspect-[3/4] object-cover" />
            <div class="md:pt-32">
                 <img src={ownerExperience} alt="Owner experience" class="w-full aspect-[3/4] object-cover" />
            </div>
        </div>
        <div class="flex justify-end">
             <p class="text-xs text-gray-400 font-light max-w-md leading-relaxed">
                Racehorse ownership through Tropical Racing combines the thrill of elite competition with the peace of mind that comes from transparent pricing and professional management. Every partner receives regular updates, access to training sessions, and the full race day experience—from paddock to winner's circle.
            </p>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-gray-950 text-white py-24 mb-24 md:mb-32">
        <div class="max-w-[1200px] mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-12 text-center">
                <div>
                    <div class="text-4xl md:text-5xl font-display text-primary-400 mb-2">$0</div>
                    <div class="text-sm text-gray-400 uppercase tracking-wider">Hidden Fees</div>
                </div>
                <div>
                    <div class="text-4xl md:text-5xl font-display text-primary-400 mb-2">100%</div>
                    <div class="text-sm text-gray-400 uppercase tracking-wider">Transparency</div>
                </div>
                <div>
                    <div class="text-4xl md:text-5xl font-display text-primary-400 mb-2">Elite</div>
                    <div class="text-sm text-gray-400 uppercase tracking-wider">Bloodstock</div>
                </div>
                <div>
                    <div class="text-4xl md:text-5xl font-display text-primary-400 mb-2">Aligned</div>
                    <div class="text-sm text-gray-400 uppercase tracking-wider">Economics</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bottom Text -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32 text-center">
        <div class="max-w-2xl mx-auto">
            <h2 class="font-display text-3xl md:text-4xl mb-6">Ready to Experience Elite Ownership?</h2>
            <p class="text-gray-600 font-light leading-relaxed mb-8">
                Join a community of passionate racing enthusiasts who demand transparency, professionalism, and aligned interests. Discover how Tropical Racing is redefining Thoroughbred ownership.
            </p>
            <a href="#apply" class="inline-block bg-primary-600 text-white px-8 py-4 text-sm uppercase tracking-widest hover:bg-primary-700 transition-colors">
                Schedule a Consultation
            </a>
        </div>
    </section>

    <!-- Bottom CTA -->
    <section class="w-full grid grid-cols-1 md:grid-cols-2 h-[600px]">
        <div class="relative group overflow-hidden">
            <img src={ctaLeft} alt="View our horses" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/30 group-hover:bg-black/40 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">View Our Portfolio</h2>
                <p class="text-sm font-light mb-8 opacity-90">Explore current partnership opportunities and meet our horses.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    View Horses
                </button>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src={ctaRight} alt="Learn more" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/30 group-hover:bg-black/40 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">Partnership Guide</h2>
                <p class="text-sm font-light mb-8 opacity-90">Download our comprehensive guide to Thoroughbred co-ownership.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    Download Guide
                </button>
            </div>
        </div>
    </section>
</div>

