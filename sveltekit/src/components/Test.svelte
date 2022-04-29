<div class="fixed w-full bg-[snow] border border-b-[gainsboro]">
<!--     TODO: hay que crear dos verciones de este componente, una cuando esta logeado y otra cuando no. -->
<!-- Vercion logeado. -->
  <div class="flex items-center py-1">
    <div class="flex-none">
      <svg class="w-6 h-6 inline-block" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
      <img class="w-12 ml-4 inline-block" src="https://res.cloudinary.com/rick-rick-torrellas/image/upload/v1651248955/clone/youtube_lcgelh.png" alt="youtube">
      <span class="font-semibold text-2xl font-roboto inline-block" >Youtube</span>
    </div>
<!-- FIXME: en pantallas mas pequenas el input, no se ve tan largo como deberia -->
<!-- FIXME: no logro colocarle el padding al placeholder. -->
<!-- TODO: Colocar el icono de lupa, cunado cliqueas el input. -->
<div class="ml-[10%] flex flex-1 bg-red-200 justify-center">
  <input class="flex-1 font-roboto border border-[gainsboro] focus:outline-none focus:border-blue-400 shadow-sm max-w-[60%]" placeholder="Buscar" type="text placeholder:pl-2">
  <button class="px-5 py-1.5 bg-[#f0f0f0] border border-[gainsboro]">
      <i class="fa-solid fa-magnifying-glass "></i>
  </button>
  <a href="/" class="rounded-full bg-gray-100 ml-4 px-3 py-1.5">
      <i class="fa-solid fa-microphone"></i>
  </a>
</div>
      <div class=" flex flex-none ">
          <i class="fa-solid fa-video text-gray-500 ml-32"></i>
          <i class="fa-solid fa-table-cells ml-4 text-xl"></i>
          <i class="fa-regular fa-bell ml-4 text-xl"></i>
  <!-- //TODO: crear el menu desplegable. -->
          <img src="/me.jpg" alt="" class="rounded-full w-10">
      </div>
  </div>
</div>
