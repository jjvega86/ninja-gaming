<script>
	export let title = '';
</script>

<div class="title">
	<img src="/controller.svg" alt="controller icon" />
	<h1>{title}</h1>
</div>

<style>
	.title {
		display: flex;
		margin: 1rem;
	}
	.title img {
		display: inline-block;
		max-width: fit-content;
		filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%) contrast(90%);
	}
	.title h1 {
		margin-left: 20px;
	}
</style>
