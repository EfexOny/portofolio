<script>

  import Step from "./step.svelte"

  let steps = [
    {name :'EcoWatch', icon: "fa-solid fa-laptop-code"},
    {name :'Thobor-Robots Gallery', icon: "fa-solid fa-robot"},
  ]

</script>

<main class="flex flex-col flex-1 p-4">
        <section id="Intro" class="grid grid-cols-2 sm:grid-cols-1  gap-10 py-8 sm:py-14">
            <div class="flex flex-col text-start sm:text-center ">
                <h2 class="text-4xl sm:text-5xl md:text-6xl">
                  Hi! Here I am, <span class="text-green-700"> Efex</span> <br/> <span class="text-green-700"> Flutter </span> Developer
                </h2>

            </div>
            <div class="pl-4 py-20 text-right sm:text-center">
              <button class=" hover:text-black  text-white font-bold py-2 px-4 border-green-700 bg-green-600 rounded">CONTACT ME</button>
          </div>
        </section>

      <section>
        <div class="grid  grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-10">
          <Step step={steps[0]}>

          </Step>
          
          <Step step={steps[1]}>

          </Step>

        </div>
      </section>



</main>