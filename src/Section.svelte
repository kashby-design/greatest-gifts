<script>
  export let number = "#";
  export let giftTitle = "Title";
  export let giftDesc = "Desc";
  export let backgroundColor = "blue";
</script>

<section class="{number}">
  <div class="content">
    <h2>{giftTitle}</h2>
    <p><mark>{giftDesc}</mark></p>
  </div>
</section>

<style>
  section {
    padding: 10em 1em 7em;
    transform: skewY(-5deg);
    color: white;
    background-image: url("https://www.transparenttextures.com/patterns/60-lines.png");
  }

  h2 {
    font-size: 8em;
    margin: 0 0 56px 0;
  }

  p {
    font-size: 2em;
    font-family: "Khula";
    margin: 0;
    padding: 0;
    color: var(--gray600);
  }

  mark {
    background-color: var(--gray100);
    padding: 8px;
    line-height: 2.3em;
  }

  .content {
    max-width: 800px;
    min-width: 400px;
    transform: skewY(5deg);
    margin: 0 auto;
  }

  @media only screen and (max-width: 500px) {
    h2 {
      font-size: 4em;
    }
    p {
      font-size: 1em;
    }
    mark {
      line-height: 3em;
    }
  }
</style>
