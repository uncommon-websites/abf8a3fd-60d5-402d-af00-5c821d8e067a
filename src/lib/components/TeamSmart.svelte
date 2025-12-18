<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-12 leading-tight">
					Built for banks<br />
					and credit unions
				</h2>

				<div class="space-y-6">
					<div class="flex items-center gap-3 text-primary-400 font-medium">
						<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
						Retail Banks
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8">
						Boost customer engagement and retention with personalized financial education that drives product adoption and lifetime value.
					</p>

					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Credit Unions
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Challenger Banks
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Digital Banks
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Community Banks
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Building Societies
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative">
                     <!-- Using a placeholder image that looks like the person in the screenshot -->
                     <!-- Since I can't use external images easily without knowing if they persist, I'll use a colored placeholder or a gradient if I can't find one. 
                     But the prompt allows me to use the screenshot as reference. I will try to simulate the UI over an image. -->
                     <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=1000&auto=format&fit=crop" alt="Person using AI" class="w-full h-full object-cover grayscale opacity-80" />
                     
                     <!-- Chat Input Overlay -->
                     <div class="absolute bottom-8 left-8 right-8 bg-white rounded-2xl p-2 shadow-2xl">
                         <div class="flex items-center gap-2 px-2 py-1">
                             <span class="text-black font-medium">Crea</span><span class="w-0.5 h-5 bg-black animate-pulse"></span>
                         </div>
                         <div class="flex justify-between items-center mt-2 px-2">
                             <div class="flex gap-4 text-gray-400">
                                 <Paperclip size={18} />
                                 <Image size={18} />
                                 <AtSign size={18} />
                                 <Smile size={18} />
                             </div>
                             <div class="w-8 h-8 bg-black rounded-full flex items-center justify-center text-white">
                                 <ArrowUp size={16} />
                             </div>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>
