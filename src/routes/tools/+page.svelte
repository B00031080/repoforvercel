<script>
    export let data;
</script>

<h1>List of all Parkside Tools</h1>
<ul>
  {#each data.tools as tool}
    <li>{tool.name} - {tool.category} - {tool.price}</li>
  {/each}
</ul>