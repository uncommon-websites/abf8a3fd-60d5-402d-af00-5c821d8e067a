<script lang="ts">
	import { Menu, X } from 'lucide-svelte';
    import { onMount } from 'svelte';

	let isMenuOpen = false;
    let isScrolled = false;

    function toggleMenu() {
        isMenuOpen = !isMenuOpen;
    }

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 20;
        };
        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<nav class="fixed top-0 left-0 w-full z-50 transition-all duration-300 {isScrolled ? 'bg-black/80 backdrop-blur-md border-b border-white/10' : 'bg-transparent'} text-white">
	<div class="max-w-[1400px] mx-auto px-6 h-20 flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="flex items-center gap-2">
			<svg width="32" height="29" viewBox="0 0 77 70" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path fill-rule="evenodd" clip-rule="evenodd" d="M33.3557 37.7678C33.3557 30.6406 24.7386 27.0712 19.6989 32.1109L10.5191 41.2908C8.26111 43.5487 4.60024 43.5487 2.34229 41.2908C0.0843386 39.0328 0.0843376 35.372 2.34229 33.114L32.7995 2.6568C35.9237 -0.467395 40.989 -0.467392 44.1132 2.6568L74.5704 33.114C76.8284 35.372 76.8284 39.0328 74.5704 41.2908C72.3125 43.5487 68.6516 43.5487 66.3936 41.2908L58.5763 33.4734C53.5366 28.4337 44.9194 32.003 44.9194 39.1303L44.9194 64.1274C44.9194 67.3206 42.3308 69.9092 39.1376 69.9092C35.9444 69.9092 33.3557 67.3206 33.3557 64.1274V37.7678Z" fill="white"/>
			</svg>
			<span class="text-2xl font-serif tracking-tight font-medium">Doshi</span>
		</a>

		<!-- Desktop Links -->
		<div class="hidden lg:flex items-center gap-8 text-sm font-medium text-gray-300">
			<a href="#platform" class="hover:text-white transition-colors">Platform</a>
			<a href="#customers" class="hover:text-white transition-colors">Customers</a>
			<a href="#integrations" class="hover:text-white transition-colors">Integrations</a>
			<a href="#pricing" class="hover:text-white transition-colors">Pricing</a>
			<a href="#about" class="hover:text-white transition-colors">About</a>
		</div>

		<!-- Right Actions -->
		<div class="hidden lg:flex items-center gap-6">
			<a href="#" class="text-sm font-medium text-white hover:text-gray-300 transition-colors">Log in</a>
			<a href="#" class="bg-primary-500 hover:bg-primary-600 text-white px-5 py-2.5 rounded-full text-sm font-medium transition-colors">
				Book a demo
			</a>
		</div>

		<!-- Mobile Menu Button -->
		<button class="lg:hidden text-white" onclick={toggleMenu}>
			{#if isMenuOpen}
				<X size={24} />
			{:else}
				<Menu size={24} />
			{/if}
		</button>
	</div>

	<!-- Mobile Menu -->
	{#if isMenuOpen}
		<div class="lg:hidden bg-black absolute top-20 left-0 w-full h-[calc(100vh-80px)] p-6 flex flex-col gap-6 overflow-y-auto border-t border-white/10">
			<a href="#platform" class="text-lg font-medium text-gray-300 hover:text-white">Platform</a>
			<a href="#customers" class="text-lg font-medium text-gray-300 hover:text-white">Customers</a>
			<a href="#integrations" class="text-lg font-medium text-gray-300 hover:text-white">Integrations</a>
			<a href="#pricing" class="text-lg font-medium text-gray-300 hover:text-white">Pricing</a>
			<a href="#about" class="text-lg font-medium text-gray-300 hover:text-white">About</a>
			<div class="h-px bg-white/10 my-2"></div>
			<a href="#" class="text-lg font-medium text-white">Log in</a>
			<a href="#" class="bg-primary-500 text-white px-5 py-3 rounded-full text-center font-medium">
				Book a demo
			</a>
		</div>
	{/if}
</nav>
