<script>
	import { Router, Route, Link } from 'svelte-routing'
	import Navbar from './components/Navbar.svelte';
	import Home from './pages/Home.svelte'

	export let url = ""
</script>

<Router>
	<Navbar />
	<Route path="/" component={Home} />
</Router>