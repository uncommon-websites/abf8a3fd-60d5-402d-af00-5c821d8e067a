<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
				Financial education that<br />
				customers actually complete
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				AI-native learning journeys embedded directly into your banking app, designed to drive engagement and build lasting customer relationships.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Gamified Learning -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Gamified Learning</h3>
					<p class="text-gray-400 text-sm">Turn financial education into an engaging game</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <!-- Game-like UI -->
                         <div class="w-full h-full border border-white/5 rounded-lg bg-gradient-to-br from-primary-950/30 to-[#0a0a0a] p-6 relative">
                             <div class="flex justify-between items-center mb-6">
                                 <div class="text-xs text-gray-400">Level 3</div>
                                 <div class="flex gap-2">
                                     <div class="w-8 h-8 rounded-full bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-xs">🏆</div>
                                     <div class="w-8 h-8 rounded-full bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-xs">⭐</div>
                                 </div>
                             </div>
                             <div class="space-y-3">
                                 <div class="bg-white/5 rounded-lg p-4 border border-white/10">
                                     <div class="text-sm mb-2">Budgeting Basics</div>
                                     <div class="h-2 bg-white/10 rounded-full overflow-hidden">
                                         <div class="h-full bg-primary-500 w-3/4"></div>
                                     </div>
                                 </div>
                                 <div class="bg-white/5 rounded-lg p-4 border border-white/10 opacity-60">
                                     <div class="text-sm mb-2">Saving Strategies</div>
                                     <div class="h-2 bg-white/10 rounded-full"></div>
                                 </div>
                                 <div class="bg-white/5 rounded-lg p-4 border border-white/10 opacity-40">
                                     <div class="text-sm mb-2">Investment 101</div>
                                     <div class="h-2 bg-white/10 rounded-full"></div>
                                 </div>
                             </div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Personalized Journeys -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Personalized Journeys</h3>
					<p class="text-gray-400 text-sm">AI adapts content to each customer's needs</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- Top stats row -->
                    <div class="flex gap-4 mb-6">
                        <div class="bg-blue-500/10 p-4 rounded w-1/3 border border-blue-500/20">
                            <div class="text-xs text-blue-300 mb-1">Revenue</div>
                            <div class="text-xl font-bold text-blue-400">14% ↗</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Productivity</div>
                            <div class="text-xl font-bold text-white">64%</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Efficiency</div>
                            <div class="text-xl font-bold text-white">7%</div>
                        </div>
                    </div>
                    
                    <!-- Chart -->
                    <div class="flex-1 w-full relative mt-4">
                         <svg class="w-full h-full overflow-visible" viewBox="0 0 100 50" preserveAspectRatio="none">
                             <!-- Grid lines -->
                             <line x1="0" y1="10" x2="100" y2="10" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="25" x2="100" y2="25" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="40" x2="100" y2="40" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             
                             <!-- Lines -->
                             <path d="M0 45 C 20 40, 40 30, 60 25 S 80 15, 100 5" fill="none" stroke="#3b82f6" stroke-width="2" />
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30" fill="none" stroke="#10b981" stroke-width="2" />
                             
                             <!-- Area under curve (fake) -->
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30 V 50 H 0 Z" fill="#10b981" fill-opacity="0.1" />
                         </svg>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Progress Tracking -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Progress Tracking</h3>
					<p class="text-gray-400 text-sm">Real-time insights into customer learning</p>
				</div>
                
                 <!-- Mockup Content - Analytics Dashboard -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4">
                    <div class="space-y-3">
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-400">Completion Rate</span>
                            <span class="text-sm font-bold text-primary-400">78%</span>
                        </div>
                        <div class="h-2 bg-white/5 rounded-full overflow-hidden">
                            <div class="h-full bg-primary-500 w-[78%]"></div>
                        </div>
                        
                        <div class="flex justify-between items-center mt-4">
                            <span class="text-xs text-gray-400">Active Learners</span>
                            <span class="text-sm font-bold text-primary-400">12.4K</span>
                        </div>
                        <div class="h-2 bg-white/5 rounded-full overflow-hidden">
                            <div class="h-full bg-primary-500 w-[92%]"></div>
                        </div>
                        
                        <div class="flex justify-between items-center mt-4">
                            <span class="text-xs text-gray-400">Avg. Session Time</span>
                            <span class="text-sm font-bold text-primary-400">8.2 min</span>
                        </div>
                        <div class="h-2 bg-white/5 rounded-full overflow-hidden">
                            <div class="h-full bg-primary-500 w-[65%]"></div>
                        </div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Embedded Integration -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Embedded Integration</h3>
					<p class="text-gray-400 text-sm">Seamlessly fits into your existing app</p>
				</div>
                
                 <!-- Mockup Content - Mobile App Integration -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-2xl p-4 w-48 shadow-2xl relative">
                        <div class="space-y-3">
                            <div class="bg-white/5 rounded-lg p-3 border border-white/10">
                                <div class="text-[10px] text-gray-400 mb-1">Accounts</div>
                                <div class="text-sm font-bold">£2,450.32</div>
                            </div>
                            <div class="bg-gradient-to-r from-primary-500/20 to-primary-600/20 rounded-lg p-3 border border-primary-500/30">
                                <div class="flex items-center gap-2 mb-1">
                                    <div class="text-[10px] text-primary-300">Learn & Earn</div>
                                    <div class="text-[8px] bg-primary-500 text-white px-1.5 py-0.5 rounded-full">NEW</div>
                                </div>
                                <div class="text-xs text-white">Complete lessons, earn rewards</div>
                            </div>
                            <div class="bg-white/5 rounded-lg p-3 border border-white/10">
                                <div class="text-[10px] text-gray-400">Payments</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Rewards & Incentives -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Rewards & Incentives</h3>
					<p class="text-gray-400 text-sm">Drive completion with meaningful rewards</p>
				</div>
                
                 <!-- Mockup Content - Rewards -->
                <div class="flex-1 relative flex flex-col gap-3">
                    <div class="bg-gradient-to-br from-primary-500/10 to-[#1a1a1a] rounded-lg p-4 border border-primary-500/20">
                        <div class="flex items-center gap-3 mb-2">
                            <div class="w-10 h-10 rounded-full bg-primary-500/20 flex items-center justify-center text-lg">🎯</div>
                            <div>
                                <div class="text-xs font-semibold">Savings Challenge</div>
                                <div class="text-[10px] text-gray-400">Complete to earn £5</div>
                            </div>
                        </div>
                        <div class="h-1.5 bg-white/10 rounded-full overflow-hidden">
                            <div class="h-full bg-primary-500 w-1/2"></div>
                        </div>
                    </div>
                    
                    <div class="bg-[#1a1a1a] rounded-lg p-4 border border-white/10">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center text-lg">🏆</div>
                            <div>
                                <div class="text-xs font-semibold">Budget Master</div>
                                <div class="text-[10px] text-gray-400">Unlock at Level 5</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
