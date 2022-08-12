<header id="topbar">
	<slot />
</header>

<style>
	#topbar {
		position: fixed;
		top: 0;
		padding: 0px;
		left: 0;
		width: 100%;
		-webkit-user-select: none;
		-moz-user-select: none;
		-ms-user-select: none;
		user-select: none;
		background: var(--bgDarkT);
		backdrop-filter: saturate(180%) blur(20px);
		-webkit-backdrop-filter: saturate(180%) blur(20px);
		height: 50px;
		display: flex;
		align-items: center;
	}
</style>
