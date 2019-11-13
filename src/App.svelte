<script>
import Router from 'svelte-spa-router'
import Home from './components/home.svelte'
import Showpage from './components/showpage.svelte'

const routes = {
    '/': Home,
    '/showpage/': Showpage,
}
	// export let name;
</script>

<style>
</style>

<body>
    <Router {routes}/>
</body>