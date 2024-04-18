<script lang="ts">
	/* the props */
	// import "open-props/index.css";
	import "open-props/src/index.css";

	/* optional imports that use the props */
	import "open-props/src/extra/normalize.css";
	import "open-props/src/extra/buttons.css";

</script>

<slot />

<style>
    :root {
		--link: #cc7633;
		--link-visited: #a2581f;
	}
</style>