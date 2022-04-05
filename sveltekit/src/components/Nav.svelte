<script>
    import Nav__State from "./../components/Nav__State.svelte";
</script>

<div class="container">
<!--     TODO: hay que crear dos verciones de este componente, una cuando esta logeado y otra cuando no. -->
<!-- Vercion logeado. -->
    <div class="flex place-items-center pt-1">
        <span class="font-light text-[20px] ml-7">
            <i class="fa-solid fa-bars" />
        </span>
        <span class="text-red-500 text-[30px] ml-8">
            <i class="fa-brands fa-youtube" />
        </span>
        <span class="font-semibold text-2xl font-roboto" >Youtube</span>
<!-- FIXME: No se coloca correctamente el margin, tal vez se tenga que usar otra propiedad que no sea margin. En dispositivos con la pantalla mas pequena no se ve igual. -->
<!-- FIXME: no logro colocarle el padding al placeholder. -->
<!-- TODO: Colocar el icono de lupa, cunado cliqueas el input. -->
        <input class="xl:ml-[20%] font-roboto border border-gray-200 focus:outline-none w-4/12 focus:border-blue-400 shadow-sm py-1.5" placeholder="Buscar" type="text placeholder:pl-2">
        <button class="px-5 py-1.5 bg-[#f0f0f0] border border-gray-200">
            <i class="fa-solid fa-magnifying-glass "></i>
        </button>
        <a href="/" class="rounded-full bg-gray-100 ml-4 px-3 py-1.5">
            <i class="fa-solid fa-microphone"></i>
        </a>
        <Nav__State />
    </div>
</div>
