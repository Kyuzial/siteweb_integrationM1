<script>
  import "../app.postcss";
  import { dev } from "$app/environment";
  import { inject } from "@vercel/analytics";

  inject({ mode: dev ? "development" : "production" });
</script>

<svelte:head>
  <title>IN001</title>
</svelte:head>

<html data-theme="light" lang="fr" />

<slot />
