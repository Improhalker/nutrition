<template>
  <footer class="relative bg-blueGray-200 pt-8 pb-6">
    
    <!-- onda decorativa mantida -->
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20 h-20"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        viewBox="0 0 2560 100"
      >
        <polygon
          class="text-blueGray-200 fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>

    <div class="container mx-auto px-4 text-center">

      <h4 class="text-2xl font-semibold text-blueGray-700">
        Portfólio de Técnica e Dietética
      </h4>

      <p class="text-blueGray-500 mt-2 text-sm">
        Curso de Nutrição — UNICAMP (FCA)
      </p>

      <p class="text-blueGray-500 mt-1 text-sm">
        Turma 025
      </p>

      <hr class="my-6 border-blueGray-300" />

      <div class="text-sm text-blueGray-500 font-semibold">
        © {{ date }} • Desenvolvido pelos alunos
      </div>
      
        <p class="text-blueGray-400 mt-2 text-xs">
          Projeto acadêmico sem fins lucrativos
        </p>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      date: new Date().getFullYear(),
    };
  },
};
</script>