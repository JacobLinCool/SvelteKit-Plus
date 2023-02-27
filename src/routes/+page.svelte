<script lang="ts">
	import { t } from "svelte-i18n";
</script>

<div class="h-full w-full flex justify-center items-center">
	<div class="prose">
		<h1>{$t("welcome")}</h1>
		<p>{$t("with-tech")}</p>
	</div>
</div>
