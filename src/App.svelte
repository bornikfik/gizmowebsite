<script>
  import './style.css'
</script>
<svelte:head>
  <title>Gizmo</title>
  <script src="https://kit.fontawesome.com/99d1a0d192.js" crossorigin="anonymous"></script>
</svelte:head>

<main>
  <div class="header">Invite Gizmo to my server</div>
  <div class="main">
    <span class="maintext">Unlike most Discord bots, <strong>Gizmo</strong> is a semi-private bot, and you will have to meet some requirements <br> to get <strong>Gizmo</strong> in your server. If you don't meet them all, no problem! You just need to meet a few.</span>
    <div class="boxes">
      <div class="infobox"><i class="fa-solid fa-at"></i>Must have an active server</div> <div class="infobox"><i class="fa-solid fa-arrow-up-right-dots"></i>Intention of growing</div>
      <div class="infobox"><i class="fa-solid fa-face-smile"></i>Over 1,000 Members</div> <div class="infobox"><i class="fa-solid fa-database"></i>Not abusive against bots</div>
      <div class="infobox"><i class="fa-brands fa-android"></i><span>Less than 5 bots in the server</span></div> <div class="infobox"><span class="meetreq">if you meet the requirements, message bornikfik#6466 <br>or universe#9088 to get Gizmo on your server</span></div>
    </div>
  </div>
</main>

<style>
  main {
    width: 57vw;
    display: flex;
    flex-direction: column;
  }
  .header {
    font-weight: 800;
    color: #aba7a7;
    font-size: 3.563rem;
  }
  .main {
    width: 100%;
    height: 100%;
    background: #2F206C;
    border-radius: 40px;
    padding: 1rem;
  }
  .boxes {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
  }
  .maintext {
    font-size: 10px;
    font-weight: 700;
  }
  .infobox {
    width: 350px;
    height: 50px;
    background: #1c1340;
    border-radius: 15px;
    font-weight: 800;
    font-size: 14px;
    height: 50px;
    line-height: 50px;
    margin: 10px;
  }
  .infobox span {
    line-height: 1.5;
    display: inline-block;
    vertical-align: middle;
  }
  .meetreq {
    font-size: 11px;
  }
  i {
    padding-right: 20px;
  }
</style>