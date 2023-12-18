<script>
  import FaUser from 'svelte-icons/fa/FaUser.svelte'
</script>

<div class="container-expand">
    <nav class="navbar navbar-expand sticky-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="/"><strong>nutricoach</strong></a>
        <a class="icon" href="user/login"><FaUser /></a>
      </div>
    </nav>
  </div>

  <style>
    .navbar-expand{
      background: linear-gradient(to right, #9681ff, hsl(0, 0%, 91%));
    }
    .icon{
      color:rgb(107, 78, 255);
      width:32px;
      height:32px;
    }
  </style>

