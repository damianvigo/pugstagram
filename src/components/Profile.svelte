<script>
  export let nickname;
  export let name;
</script>

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

<!-- Profile.svelte -->
<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <img
        src="https://static.platzi.com/media/avatars/avatars/Damian_4d1dd3b8-a733-4ea1-ab0b-799052a5942a.jpg"
        alt="" />
    </div>
    <div class="Profile-info">
      <h2>Dami</h2>
      <span>Frontend Developer</span>
    </div>
  </div>
</div>
