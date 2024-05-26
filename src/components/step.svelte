<script>
    export let step;
</script>

<a href="{step.href}" target="_blank" class="p-4  sm:p-6 md:p-8 flex flex-col gap-4 rounded-lg border border-solid border-green-600 text-center group cursor-pointer hover:border-green-300 duration-200">
  <div class="bg-slate-950 grid place-items-center px-4 test-5xl md:test-6xl">
      <i class={step.icon}/>
  </div>

  <h3> {step.name}</h3>
</a>