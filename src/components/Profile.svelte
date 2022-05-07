<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <!-- svelte-ignore a11y-img-redundant-alt -->
      <img
        src="https://arepa.s3.amazonaws.com/oscar.png"
        alt="Profile Picture"
      />
    </div>
    <div class="Profile-info">
      <h2>gndx</h2>
      <span>Oscar Barajas</span>
    </div>
  </div>
</div>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>
