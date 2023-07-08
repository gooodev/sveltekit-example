<svelte:options customElement="custom-card" />

<div>
  <slot />
  <p>This is a great picture!</p>
</div>

<style>
  div {
    border: 1px solid #ccc;
    border-radius: 4px;
    padding: 1rem;
  }
</style>
