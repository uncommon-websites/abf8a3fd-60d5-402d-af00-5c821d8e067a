<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-serif font-normal mb-16">Pricing</h2>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Enterprise -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Enterprise</h3>
				<p class="text-gray-400 text-sm mb-6">Custom pricing</p>
				<button class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors">
					Contact sales
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">FOR LARGE BANKS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited active learners</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom content development</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>White-label branding</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Advanced AI personalization</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated success manager</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>SLA with 24/7 support</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Full API access</span>
					</li>
				</ul>
			</div>

			<!-- Growth -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Growth</h3>
				<p class="text-primary-400 text-sm mb-6">From £2,500/month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Start pilot
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">FOR GROWING BANKS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 50K active learners</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Core content library</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Gamification & rewards engine</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>AI personalization</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Analytics dashboard</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Mobile SDK integration</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Email & chat support</span>
					</li>
				</ul>
			</div>

			<!-- Pilot -->
			<div>
				<h3 class="text-xl font-bold mb-2">Pilot</h3>
				<p class="text-primary-300 text-sm mb-6">From £500/month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Get started
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">PROOF OF CONCEPT</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 5K active learners</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>3-month pilot program</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Essential content library</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Basic gamification</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Progress tracking</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>SDK integration support</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Email support</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>
