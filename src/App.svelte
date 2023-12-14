<script>
  let name = 'Svelte';
  let src = 'https://uploads.dailydot.com/2018/07/yoda-star-wars-meme.jpg?auto=compress&fm=pjpg'
  let string = 'Some <strong>string</strong> with html.';
</script>

<img {src} alt="Some text {name}" width="500px"/>
<h1>Hello {name.toLowerCase()}</h1>
<p>{@html string}</p>

<style>
  h1 {
    color: red;
  }
</style>