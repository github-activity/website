<script lang="ts">
  import ChangelogLink from "./changelog-link.svelte";

  export let date: string;
  export let href: string;
</script>

<div class="w-full md:w-4/12">
  <ChangelogLink class="mb-xx-small" {href}>
    {date}
  </ChangelogLink>
</div>
