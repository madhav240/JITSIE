<script>
	import '../app.css';
	import Footer from '../lib/components/Footer.svelte';

	import Navbar from '../lib/components/Navbar.svelte';
</script>

<Navbar />
<slot />

<div class="mt-32">
	<Footer />
</div>
