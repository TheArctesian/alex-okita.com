<script>
  import "../app.css";
</script>
<style>
    @import url('https://fonts.googleapis.com/css2?family=M+PLUS+Rounded+1c:wght@100;300;400;500;700;800&display=swap');
    main{
        background-color:#272727;
    } 
    div{
        padding-top: 1rem;
        padding-bottom: 1rem;
        background-color:#272727;
        color: #E7E7E7;
        font-family: 'M PLUS Rounded 1c', sans-serif;

    }
    a{
        margin: auto;
        text-decoration: none;
        transition: all ease-in-out 400ms;
    }
    a:hover{
        color: #6B6B6B;
    }
</style>
<div class="flex alight-center text-center ">
    <a href="/">Home</a>
    <a href="/About">About</a>
    <a href="/Contact">Contact</a>
</div>

<slot />
