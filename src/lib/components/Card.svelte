<script lang="ts">
  export let src: string;
  export let alt: string;
</script>

<div>
  <img {src} {alt} width={300} height={200} />
  <p>This is a great picture!</p>
</div>

<style>
  div {
    border: 1px solid #ccc;
    border-radius: 4px;
    padding: 1rem;
  }
</style>
