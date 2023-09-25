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
	import fly from './transitions.js';
	export let open = false;
</script>

{#if open}
	<div class="drawer" transition:fly={{ x: '100%' }}>
		<center><h1>Attribution</h1></center>
		<p>
			For the ease of implementation drawing, I drew upon Randall Munroe's wizardry at
			https://xkcd.com/.
		</p>

		<p>
			The Clash 'o Clans themed user interface surfaces some video game fun in designing a user
			interface.
		</p>
		<p>
			Instructions: Move your cursor over the image to create a magnifying glass. If the title that
			pops us is annoying, then click the mouse to get rid of it.
		</p>
	</div>
{/if}

<style>
	.drawer {
		position: fixed;
		z-index: 10;
		top: 0;
		right: 0;
		padding: 25px;
		height: 100vh;
		width: 400px;
		border-left: 1px solid rgba(0, 0, 0, 0.1);
		box-shadow: -2px 0px 6px -1px rgba(0, 0, 0, 0.1);
		background: #4a4b4a;
		opacity: 0.6;
		backdrop-filter: blur(20px);
		overflow: auto;
	}
	div {
		font-size: 20px;
		color: #ffffff;
		font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
	}
</style>
