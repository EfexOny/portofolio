<script>

    let tabs = [
        {name: 'Projects', link: "#projects"},
        {name: 'Github', link: "#github"},

    ]
</script>

<header class=" bg-gray-800 sticky z-[10] top-0 duration-200 flex px-6 items-center  justify-between ">
      <h1 class="font-bold poppins text-4xl sm:text-6xl duration-700 hover:animate-pulse sm:pl-20 ">
          EF<span class="text-green-700">X</span>
      </h1>
      <div class="sm:flex items-center gap-4 hidden text-4xl">
            {#each tabs as tab,index }

                <a href="{tab.link}" class="duration-700 hover:text-green-700">
                  <p>{tab.name}</p>
                </a>
              
            {/each}
      </div>
</header>




