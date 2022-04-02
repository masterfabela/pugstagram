<script>
  import Comments from './Comments.svelte';
</script>

<div class="Card">
  <div class="Card-container">
    <div class="Card-header">
      <div class="Card-user">
        <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="" />
        <h2>Elmo.pug</h2>
        <span>Bogota, Colombia</span>
      </div>
      <div class="Card-settings">
        <i class="fa-solid fa-gear" />
      </div>
    </div>
    <div class="Card-photo">
      <figure>
        <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="" />
      </figure>
    </div>
    <div class="Card-icons">
      <div class="Card-icons-first">
        <i class="fa-solid fa-heart" />
        <i class="fa-solid fa-paper-plane" />
      </div>
      <div class="Card-icons-second">
        <i class="fa-solid fa-bookmark" />
      </div>
    </div>
    <div class="Card-description">
      <h3>elmo.pug</h3>
      <span>Hola!</span>
    </div>
    <Comments />
  </div>
</div>
