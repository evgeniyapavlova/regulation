<script>
	import Logo from './Logo.svelte';
</script>

<header>
	<section>
		<Logo />

		<div class="header-buttons">
			<button class="button button-secondary">Log In</button>
			<button class="button button-primary">Sign In</button>
		</div>
	</section>
</header>

<style>
	section {
		display: flex;
		align-items: center;
		justify-content: space-between;
	}

	header {
		padding: 10px 0;
	}

	.header-buttons {
		display: flex;
		align-items: center;
		justify-content: flex-end;
		gap: 8px;
	}
</style>
