<script lang="ts">
  export let href: string;
  export let title: string;
  let hovered = false;

  const handleHover = () => {};
</script>

<div on:mouseover={(e) => (hovered = true)}>
  <a{href}>
    <p>{title}</p>
  </a>
</div>

<style>
  /* your styles go here */
</style>
