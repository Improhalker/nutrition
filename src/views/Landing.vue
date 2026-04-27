<template>
  <div>
    <navbar />
    <main>
      <!-- Hero Section - Adaptado para Nutrição -->
      <div
        class="relative pt-16 pb-32 flex content-center items-center justify-center min-h-screen-75"
      >
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="
            background-image: url('https://images.unsplash.com/photo-1490645935967-10de6ba17061?ixlib=rb-1.2.1&auto=format&fit=crop&w=1953&q=80');
          "
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-75 bg-black"
          ></span>
        </div>
        <div class="container relative mx-auto">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
              <div class="md:pr-12">
                <h1 class="text-white font-semibold text-5xl">
                  Portfolio de Receitas<br/>Nutrição UNICAMP
                </h1>
                <p class="mt-4 text-lg text-blueGray-200">
                  Projeto desenvolvido pelos alunos do curso do 3º semestre de Nutrição, turma de 2025 para compartilhar, as receitas aprendidas em aula, combinando ciência, sabor e saúde.
                </p>
                <p class="mt-2 text-md text-blueGray-300">
                  Equipe: Luana Domingos Casagrande, Laís Bordini Mestriner, Léo Castro Doizé, Julia Gomes Brandão Clini, Ana Luiza Soares Lera
                </p>
              </div>
            </div>
          </div>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden h-70-px"
          style="transform: translateZ(0);"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-blueGray-200 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </div>

      <!-- Seção da Receita Principal: POKE VEGANO -->
      <section class="pb-20 bg-blueGray-200 -mt-24">
        <div class="container mx-auto px-4">
          
                   <!-- Título da Receita -->
          <div class="flex flex-wrap justify-center text-center mb-16 pt-8">
            <div class="w-full lg:w-8/12 px-4">
              <h2 class="mt-12 text-center text-2xl font-bold text-emerald-700 py-4">
                  POKE VEGANO
                </h2>
            </div>
          </div>

          <!-- Cards de Ingredientes (substituindo os cards antigos) -->
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-6/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-emerald-500"
                  >
                    <i class="fas fa-carrot"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Ingredientes do Poke</h6>
                  <div class="mt-2 mb-4 text-blueGray-500 text-left">
                    <ul class="list-disc pl-5">
                      <li>1/2 manga palmer</li>
                      <li>1/4 cebola roxa picada</li>
                      <li>30g amendoim torrado sem sal</li>
                      <li>1/2 pepino japonês</li>
                      <li>6 unidades de tomate cereja</li>
                      <li>1 xícara de repolho roxo ou verde</li>
                      <li>1/4 xícara de cebolinha</li>
                      <li>1 cenoura</li>
                      <li>1/4 xícara de gergelim branco e preto</li>
                      <li>1/2 xícara de couve picada</li>
                      <li>1/2 xícara de grão de bico cozido</li>
                      <li>1/2 xícara de arroz japonês cozido</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>

            <div class="w-full md:w-6/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-500"
                  >
                    <i class="fas fa-flask"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Ingredientes do Molho</h6>
                  <div class="mt-2 mb-4 text-blueGray-500 text-left">
                    <ul class="list-disc pl-5">
                      <li>1 dente de alho</li>
                      <li>1/2 limão</li>
                      <li>1 xícara de molho shoyo</li>
                      <li>1 colher de chá de óleo de gergelim ou azeite</li>
                      <li>1 colher de café de gengibre em pó</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Modo de Preparo -->
          <div class="flex flex-wrap items-center mt-8">
            <div class="w-full md:w-6/12 px-4 mr-auto ml-auto">
              <div
                class="text-emerald-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
              >
                <i class="fas fa-utensils text-xl"></i>
              </div>
              <h3 class="text-3xl mb-2 font-semibold leading-normal">
                Modo de Preparo
              </h3>
              <div class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600">
                <ol class="list-decimal pl-5 space-y-3">
                  <li>Higienize todos os legumes e hortaliças. Após escorrer a água, pique cada ingrediente conforme indicado na lista.</li>
                  <li>Prepare o molho: misture o alho, suco de limão, shoyu, óleo de gergelim (ou azeite) e gengibre.</li>
                  <li>Monte o poke: coloque o arroz no fundo, adicione os ingredientes por cima e acrescente o grão-de-bico.</li>
                  <li>Finalize: regue com o molho e finalize com amendoim e gergelim.</li>
                </ol>
              </div>
            </div>

            <!-- Vídeo da Receita -->
            <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg overflow-hidden"
              >
                <video 
                  controls 
                  class="w-full align-middle"
                  poster="/img-nutrition/poke-vegano.webp"
                >
                  <source src="/img-nutrition/IMG_2221.mp4" type="video/mp4" />
                  Seu navegador não suporta vídeos.
                </video>
                <div class="p-4 bg-emerald-50 text-center">
                  <p class="text-sm text-emerald-700">Vídeo da apresentação do Poke Vegano - Técnica Dietética</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Galeria de Imagens (substituindo a seção de heroes) -->
          <div class="flex flex-wrap justify-center text-center mt-24 mb-12">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold">Galeria da Receita</h2>
              <p class="text-lg leading-relaxed m-4 text-blueGray-500">
                Registros fotográficos do preparo e apresentação final do Poke Vegano
              </p>
            </div>
          </div>

          <div class="flex flex-wrap justify-center">
            <div class="w-full md:w-4/12 lg:w-4/12 px-4 mb-8">
              <div class="rounded-lg overflow-hidden shadow-lg bg-white">
                <img
                  alt="Poke Vegano - Foto 1"
                  src="/img-nutrition/poke-vegano.webp"
                  class="w-full h-64 object-cover"
                />
                <div class="p-3 text-center text-sm text-blueGray-600">Montagem do Poke</div>
              </div>
            </div>
            <div class="w-full md:w-4/12 lg:w-4/12 px-4 mb-8">
              <div class="rounded-lg overflow-hidden shadow-lg bg-white">
                <img
                  alt="Poke Vegano - Foto 2"
                  src="/img-nutrition/poke-vegano2.webp"
                  class="w-full h-64 object-cover"
                />
                <div class="p-3 text-center text-sm text-blueGray-600">Visão dos ingredientes</div>
              </div>
            </div>
            <div class="w-full md:w-4/12 lg:w-4/12 px-4 mb-8">
              <div class="rounded-lg overflow-hidden shadow-lg bg-white">
                <img
                  alt="Poke Vegano - Foto 3"
                  src="/img-nutrition/poke-vegano3.webp"
                  class="w-full h-64 object-cover"
                />
                <div class="p-3 text-center text-sm text-blueGray-600">Apresentação final</div>
              </div>
            </div>
          </div>

                  <!-- Integrantes do Grupo com Foto -->
          <div class="flex flex-wrap justify-center mt-12">
            <div class="w-full lg:w-8/12 px-4">
              <div class="bg-white rounded-lg shadow-lg p-6 text-center">
                
                <div class="flex justify-center">
                  <img
                    alt="Integrantes do grupo - Nutrição UNICAMP"
                    src="/img-nutrition/amigos.webp"
                    class="rounded-lg shadow-md max-w-full h-auto"
                  />
                </div>
                
              </div>
            </div>
          </div>

          <!-- Membros da Equipe -->
          <div class="flex flex-wrap justify-center text-center mt-24 mb-12">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold">Nosso Grupo</h2>
              <p class="text-lg leading-relaxed m-4 text-blueGray-500">
                Alunos de Nutrição - Disciplina de Técnica Dietética
              </p>
            </div>
          </div>

            <div class="flex flex-wrap justify-center">
            <div class=" md:w-3/12 lg:w-2/12 px-4 mb-8">
              <div class="text-center">
              <div class="w-32 h-32 bg-emerald-100 rounded-full mx-auto flex items-center justify-center">
                <i class="fas fa-user-graduate text-5xl text-emerald-600"></i>
              </div>
              <h5 class="text-xl font-bold mt-4">Luana Domingos Casagrande</h5>
              <p class="text-sm text-blueGray-400">Líder do grupo</p>
              </div>
            </div>
            <div class=" md:w-3/12 lg:w-2/12 px-4 mb-8">
              <div class="text-center">
              <div class="w-32 h-32 bg-emerald-100 rounded-full mx-auto flex items-center justify-center">
                <i class="fas fa-user-graduate text-5xl text-emerald-600"></i>
              </div>
              <h5 class="text-xl font-bold mt-4">Laís Bordini Mestriner</h5>
              <p class="text-sm text-blueGray-400">Responsável pelo preparo</p>
              </div>
            </div>
            <div class=" md:w-3/12 lg:w-2/12 px-4 mb-8">
              <div class="text-center">
              <div class="w-32 h-32 bg-emerald-100 rounded-full mx-auto flex items-center justify-center">
                <i class="fas fa-user-graduate text-5xl text-emerald-600"></i>
              </div>
              <h5 class="text-xl font-bold mt-4">Léo Castro Doizé</h5>
              <p class="text-sm text-blueGray-400">Registro fotográfico</p>
              </div>
            </div>
            <div class=" md:w-3/12 lg:w-2/12 px-4 mb-8">
              <div class="text-center">
              <div class="w-32 h-32 bg-emerald-100 rounded-full mx-auto flex items-center justify-center">
                <i class="fas fa-user-graduate text-5xl text-emerald-600"></i>
              </div>
              <h5 class="text-xl font-bold mt-4">Julia Gomes Brandão Clini</h5>
              <p class="text-sm text-blueGray-400">Análise nutricional</p>
              </div>
            </div>
            <div class=" md:w-3/12 lg:w-2/12 px-4 mb-8">
              <div class="text-center">
              <div class="w-32 h-32 bg-emerald-100 rounded-full mx-auto flex items-center justify-center">
                <i class="fas fa-user-graduate text-5xl text-emerald-600"></i>
              </div>
              <h5 class="text-xl font-bold mt-4">Ana Luiza Soares Lera</h5>
              <p class="text-sm text-blueGray-400">Edição do vídeo</p>
              </div>
            </div>
            </div>
        </div>
      </section>

    </main>
    <footer-component />
  </div>
</template>

<script>
import Navbar from "@/components/Navbars/AuthNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

export default {
  components: {
    Navbar,
    FooterComponent,
  },
};
</script>