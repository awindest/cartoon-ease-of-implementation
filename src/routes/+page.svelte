<!--                                  
╭━━╮╱╱╱╱╭╮╱╱╱╱╱╭╮╱╭╮╱╱╱╱╱╭╮            ━╮ ╭━
╰┫┣╯╱╱╱╱┃┃╱╱╱╱╭╯╰╮┃┃╱╱╱╱╱┃┃             | |
╱┃┃╭━╮╭━╯┣━━┳━┻╮╭╯┃┃╱╱╭━━┫╰━┳━━╮       ╱ o \
╱┃┃┃╭╮┫╭╮┃┃━┫━━┫┃╱┃┃╱╭┫╭╮┃╭╮┃━━┫      ╱_____\
╭┫┣┫┃┃┃╰╯┃┃━╋━━┃╰╮┃╰━╯┃╭╮┃╰╯┣━━┃     ╱    o  \  
╰━━┻╯╰┻━━┻━━┻━━┻━╯╰━━━┻╯╰┻━━┻━━╯    (__o______)  

Yet another science experiment from Indest Labs.

Recommend viewing in Visual Source Code.
-->
<script>
	import IndestLabs from '$lib/components/IndestLabs.svelte';
	import Hamburger from '$lib/components/Hamburger.svelte';
	let open = false;
</script>

<body>
	<!-- We default to under construction until the route is ready. -->
	<div class="center">
		<p>Site under construction. 🚀<br />Come back next Tuesday.</p>
	</div>

	<Hamburger bind:open />
</body>

<style>
	.center {
		text-align: center;
		font-size: 5em;
		font-family: Helvetica, sans-serif;
		color: #ffffff;
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}
</style>
