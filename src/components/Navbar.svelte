<script>

  const routes = [

      {
        "id"  : 1,
        "name" : "home",
        "link" : "/"
      },
      {
        "id"  : 2,
        "name" : "about",
        "link" : "/about"
      },
      {
        "id"  : 3,
        "name" : "dashboard",
        "link" : "/dashboard"
      }
  ]


</script>

<div >
    {#each routes as route (route.id)}
       <h1><a href={route.link}>{route.name}</a></h1> 
    {/each}

</div>