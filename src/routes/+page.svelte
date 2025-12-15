<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-0to9-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-0to9-primary)]"></span>
                        <span class="text-white text-sm font-medium">European Fintech</span>
                        <span class="text-gray-400 text-sm">Venture Builder</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Turn fintech ideas into funded companies.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        We provide the infrastructure, capital, and experienced builder teams that fintech entrepreneurs need to launch in Europe. From zero to success—with licenses, compliance, and funding ready to go.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Apply Now
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Learn More
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <img src="/generated/image-a-focused-fintech-entrepreneur-working-o-1765807569729-0.webp" alt="Fintech entrepreneur at work" class="w-full h-full object-cover" />
                    </div>

                    <!-- Card 2 (Center) -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <img src="/generated/image-a-diverse-team-of-builders-collaborating-1765807574165-1.webp" alt="Team collaboration" class="w-full h-full object-cover" />
                    </div>

                    <!-- Card 3 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <img src="/generated/image-close-up-of-hands-sketching-fintech-prod-1765807577684-2.webp" alt="Building fintech products" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>
        </section>

        <!-- Founder Quote Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <div class="max-w-3xl mx-auto text-center">
                    <p class="text-xl md:text-2xl text-gray-300 italic leading-relaxed">
                        "Building in finance is harder than it should be. The system is too slow and too complex."
                    </p>
                    <p class="text-gray-500 mt-4">— Oliver Hildebrandt, Founder</p>
                </div>
            </div>
        </section>

        <!-- Core Value Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-0to9-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Built by Entrepreneurs</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">From zero to success.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">From idea to impact.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Image Card -->
                    <div class="rounded-3xl overflow-hidden shadow-2xl border border-white/10">
                        <img src="/generated/image-oliver-hildebrandt-a-seasoned-fintech-fo-1765807581064-3.webp" alt="Oliver Hildebrandt - 0TO9 Founder" class="w-full h-full object-cover aspect-[4/3]" />
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">17 years. 5 companies. One mission.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Oliver Hildebrandt built five fintech companies over seventeen years. He learned what works, what doesn't, and what slows builders down. 0TO9 exists to help you avoid those delays.
                        </p>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            We're builders, not bankers. Come as you are—with drive, with curiosity, with a spark.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">What We Offer</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything you need to launch.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Nothing you don't.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        See how it works
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-0to9-primary)]"></span>
                                Infrastructure
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Capital</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Builder Teams</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Regulatory Licenses</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Compliance Support</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Infrastructure" 
                            description="Launch fast with ready-to-go infrastructure. We provide the financial backbone, technical systems, and operational framework so you can focus on building your product, not reinventing the wheel."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Capital" 
                            description="Get funded to grow. We invest in fintech entrepreneurs who have the vision and drive to build something meaningful. Our capital helps you scale without the typical fundraising delays."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Builder Teams" 
                            description="Work with experienced builders. Our teams have been through it all—the regulatory hurdles, the competitive battles, the setbacks, and the wins. We know what it takes to succeed in fintech."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Regulatory Licenses" 
                            description="Skip the licensing nightmare. 0TO9 AB operates as a credit market company under Finansinspektionen supervision. Launch under our licenses and avoid years of regulatory delays."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Compliance Support" 
                            description="Stay compliant, stay focused. Our compliance infrastructure and regulatory reporting systems handle the complex requirements, so you can concentrate on building great products for customers."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Philosophy Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-cyan-100 to-teal-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-cyan-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        "Everybody is a nobody without a team—but with a great team of devoted people, we can build, or rebuild, anything."
                    </h2>
                    <p class="text-gray-600 text-lg">That's the 0TO9 philosophy. We're builders, not bankers.</p>
                </div>

                <!-- Application Process Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Four steps to becoming a 0TO9 company</p>
                    
                    <div class="grid md:grid-cols-4 gap-6">
                        <!-- Step 1 -->
                        <div class="bg-white rounded-3xl p-8 border border-gray-200 hover:border-gray-300 transition-all">
                            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center text-gray-900 font-bold text-xl mb-6">1</div>
                            <h3 class="text-xl font-bold text-gray-900 mb-3">Send CV</h3>
                            <p class="text-gray-600 text-sm">Submit your application via our website. We review within one week if it matches our focus areas.</p>
                        </div>

                        <!-- Step 2 -->
                        <div class="bg-white rounded-3xl p-8 border border-gray-200 hover:border-gray-300 transition-all">
                            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center text-gray-900 font-bold text-xl mb-6">2</div>
                            <h3 class="text-xl font-bold text-gray-900 mb-3">Meet the Crew</h3>
                            <p class="text-gray-600 text-sm">Get to know our team. We assess the experience, the idea, and most importantly—the personality fit.</p>
                        </div>

                        <!-- Step 3 -->
                        <div class="bg-white rounded-3xl p-8 border border-gray-200 hover:border-gray-300 transition-all">
                            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center text-gray-900 font-bold text-xl mb-6">3</div>
                            <h3 class="text-xl font-bold text-gray-900 mb-3">Sign the Deal</h3>
                            <p class="text-gray-600 text-sm">Formalize the partnership. We structure the agreement to align incentives and set clear expectations.</p>
                        </div>

                        <!-- Step 4 -->
                        <div class="bg-white rounded-3xl p-8 border border-gray-200 hover:border-gray-300 transition-all">
                            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center text-gray-900 font-bold text-xl mb-6">4</div>
                            <h3 class="text-xl font-bold text-gray-900 mb-3">Welcome to 0TO9</h3>
                            <p class="text-gray-600 text-sm">Onboarding begins. You get access to infrastructure, capital, and the team that will help you build.</p>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-teal-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Financial innovation shapes our lives. <span class="text-[var(--color-0to9-primary)]">That's why we love fintech.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Behind every big leap in how we save, pay, build, and grow, there's a big idea backed by a great team. Let's build yours together.
                        </p>
                        <button class="bg-white hover:bg-gray-100 text-black px-8 py-3 rounded-full font-medium transition-colors">
                            Start Your Application
                        </button>
                    </div>
                </div>

                <!-- Transparency Section -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-8">
                        Regulated. Transparent. <span class="text-gray-400">Built to last.</span>
                    </h2>
                    <p class="text-gray-600 text-lg mb-12 max-w-2xl mx-auto">
                        0TO9 AB operates as a credit market company under the supervision of Finansinspektionen (Swedish Financial Supervisory Authority). We publish quarterly liquidity reports and annual financial statements.
                    </p>
                    
                    <div class="grid md:grid-cols-3 gap-6 max-w-4xl mx-auto">
                        <div class="bg-white rounded-2xl p-8 border border-gray-200">
                            <div class="text-4xl font-bold text-gray-900 mb-2">17+</div>
                            <div class="text-gray-600">Years of Fintech Experience</div>
                        </div>
                        <div class="bg-white rounded-2xl p-8 border border-gray-200">
                            <div class="text-4xl font-bold text-gray-900 mb-2">5</div>
                            <div class="text-gray-600">Companies Built by Founder</div>
                        </div>
                        <div class="bg-white rounded-2xl p-8 border border-gray-200">
                            <div class="text-4xl font-bold text-gray-900 mb-2">EU</div>
                            <div class="text-gray-600">Licensed & Regulated</div>
                        </div>
                    </div>
                </div>

                <!-- Reports Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-4">Financial transparency matters.</h2>
                    <p class="text-gray-600 mb-12">Access our quarterly liquidity reports and annual financial statements.</p>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Report 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-100 to-gray-200 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <svg class="w-16 h-16 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Financial Reports</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-cyan-600 transition-colors">2024 Annual Report</h3>
                        </div>
                        <!-- Report 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-100 to-gray-200 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <svg class="w-16 h-16 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 17v-2m3 2v-4m3 4v-6m2 10H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Liquidity Disclosure</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-cyan-600 transition-colors">Q3 2025 Liquidity Risk Report</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

