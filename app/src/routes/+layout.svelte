<script>
  import "../app.css";
</script>
<style>
    @import url('https://fonts.googleapis.com/css2?family=M+PLUS+Rounded+1c:wght@100;300;400;500;700;800&display=swap');
    div{
        padding-top: 1rem;
        padding-bottom: 1rem;
        background-color: var(--fg);

    }
    a{
        margin: auto;
        text-decoration: none;
        transition: all ease-in-out 400ms;
    }
    a:hover{
        color: var(--pri);
    }
    :global(body) {
        background-color: var(--bg);
        font-family: 'M PLUS Rounded 1c', sans-serif;
        color: var(--text)
    }
</style>
<div class="flex alight-center text-center ">
    <a href="/">Home</a>
    <a href="/About">About</a>
    <a href="/Contact">Contact</a>
</div>

<slot />
