<script>
    import Alex from './Alexander_Okita.webp'
</script>
<div class="wrapper">
    <div class="cover">
        <div class="cover-text">
            <h1 class="text-4xl">Alex Okita</h1>
            <p3 class="italic text-xl">San Francisco</p3>
        </div>
        <img class="shadow-2xl" src={Alex}>
    </div>
    
    <div class="blerb shadow-2xl">
        <p>Everything they do is so dramatic and flamboyant. It just makes me want to set myself on fire. - Lucille Bluth. Do the right thing here. String this blind girl along so that dad doesn't have to pay his debt to society. I am getting rid of this thing. It has caused me nothing but pride and self-respect. Mr. Zuckerkorn, you've been warned about touching. Barry: You said spanking. Probably out there without a flipper, swimming around in a circle, freaking out his whole family. I'm in Vegas this week and would like to point out the Blue Man Group is *actually* hiring. The support group? Those are balls.
    
    Don't ask "Can I"… ask "I Can!" Never once touched my per diem. I'd go to Craft Service, get some raw veggies, bacon, Cup-A-Soup…baby, I got a stew goin'. It walked on my pillow!
        </p>
        <p class="italic float-right">
        <br>
            filler text from Bluth Ipsum
        </p>
    
    </div>
</div>

<style>
    .cover{
        flex: 0.25;
        margin-top: 1rem;
        flex-basis: 50%;
        justify-content: center;
    }
    img{
        justify-content: center;
        margin:auto;
        border-radius: 2rem;
        transition: all ease-in-out 200ms;
    }
    img:hover{
        transition: all ease-in-out 200ms;
        transform: scale(0.98);
        filter: blur(1px);
  z-index: 1;
    }

    .blerb{
        align-self: center;
        margin: auto;
        margin-left: 1rem;
        height: fit-content;
        border: 0.3rem solid #8C8273;
        border-radius: 2rem;
        padding: 1rem;
        flex: 50%;

    }
    
    .cover-text{
        margin-top: 1rem;
        text-align: center;
    }
    .wrapper{
        height: 80vh;
        display: flex;
        background-color: #181A1B;
        color: white;
    }
    @media (max-width: 750px) {
        img{
            width: 80vw;
        }
        .cover{
            flex:0.1;
        }
        .blerb{
            margin-top: 1rem;
            flex: 0.1;
            margin-right: 0;
        }
        .wrapper{
            height: fit-content;
            flex-direction: column;
        }
    }
</style>

