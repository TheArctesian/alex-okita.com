<script>
  import Alex from "./Alexander_Okita.webp";
  import "../app.css";
</script>

<div class="wrapper">
  <div class="cover">
    <div class="cover-text">
      <h1 class="text-4xl">Alex Okita (沖田偉)</h1>
      <p3 class="italic text-xl">San Francisco, Hong Kong</p3>
    </div>
    <br />
    <img class="" src={Alex} />
  </div>

  <div class="blerb shadow-2xl">
    <p>
      Everything they do is so dramatic and flamboyant. It just makes me want to
      set myself on fire. - Lucille Bluth. Do the right thing here. String this
      blind girl along so that dad doesn't have to pay his debt to society. I am
      getting rid of this thing. It has caused me nothing but pride and
      self-respect. Mr. Zuckerkorn, you've been warned about touching. Barry:
      You said spanking. Probably out there without a flipper, swimming around
      in a circle, freaking out his whole family. I'm in Vegas this week and
      would like to point out the Blue Man Group is *actually* hiring. The
      support group? Those are balls.
    </p>
    <p class="italic float-right">
      <br />
      filler text from Bluth Ipsum alex pls change this
    </p>
  </div>
</div>

<style>
  .cover {
    justify-content: center;
    align-items: center;
    flex: 1;
    margin: 5%;
    margin-top: 20vh;
    border-radius: 1rem;
    background-color: var(--fg);
  }
  img {
    justify-content: center;
    margin: auto;
    border-radius: 2rem;
    transition: all ease-in-out 200ms;
    padding: 1rem;
  }

  img:hover {
    transition: all ease-in-out 200ms;
    transform: scale(0.98);
    z-index: 1;
  }

  .blerb {
    flex: 1;
    border-radius: 0.5rem;
    padding: 1rem;
    justify-content: center;
    align-items: center;
    margin: 10%;
  }

  .cover-text {
    margin-top: 1rem;
    text-align: center;
  }
  .wrapper {
    display: flex;
    height: 80vh;
    justify-content: space-around;
    align-items: center;
  }
  @media (max-width: 750px) {
    img {
      width: 80vw;
      padding: 1rem;
    }
    .cover {
    }
    .blerb {
    }
    .wrapper {
      height: fit-content;
      flex-direction: column;
    }
  }
</style>
