<script context="module">
  export function load({ error }) {
    return {
      props: { message: error.message },
    };
  }
</script>

<script>
  export let message;
</script>

<div class="error">
    <h1>Ooops</h1>
    <p>{message}</p>
    <a href="/guides">View all Guides...</a>
</div>

<style>
    .error{
        margin-bottom: 60px;
        text-align: center;
    }
</style>