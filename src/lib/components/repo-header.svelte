<script lang="ts">
  let className = '';
  export let repo: string;
  export let repoLink = '';
  export let owner: string;
  export { className as class };
</script>

<div>
  <a
    target="_blank"
    class="text-neutral-500 transition-all duration-200 hover:text-eddiehub-200 active:text-eddiehub-200 {className}"
    href={repoLink}>{owner}/{repo}</a
  >
</div>
