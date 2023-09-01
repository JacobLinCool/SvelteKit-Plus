<script lang="ts">
	import { t } from "svelte-i18n";
</script>

<div class="flex h-full w-full items-center justify-center">
	<div class="prose">
		<h1>{$t("welcome")}</h1>
		<p>{$t("with-tech")}</p>
	</div>
</div>
