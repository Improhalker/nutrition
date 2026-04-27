<template>
  <div>
    <index-navbar />
    <section class="header relative pt-16 items-center flex h-fit md:max-h-860-px">
      <div class="container mx-auto items-center flex flex-wrap" style="z-index: 5">
        <div class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4">
          <div class="md:pt-32 sm:pt-0 z-index-5">
            <h2 class="font-semibold text-4xl text-blueGray-600">
              Dos livros às panelas
            </h2>

            <h3 class="mt-4 text-xl text-blueGray-500 font-medium">
              É aqui que a ciência da nutrição sai dos livros e ganha vida nas panelas.
            </h3>

            <p class="mt-6 text-lg leading-relaxed text-blueGray-500">
              A disciplina Técnica e Dietética, carinhosamente apelidada de TD, sem
              dúvidas, é uma das mais esperadas pelos alunos da graduação em Nutrição. É
              nela que temos a oportunidade de colocar a mão na massa e demonstrar nossas
              habilidades culinárias (ou desenvolvê-las).
            </p>

            <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
              Por meio deste site, nós, alunos de Nutrição 025 da Universidade Estadual de
              Campinas (Unicamp) - Faculdade de Ciências Aplicadas (FCA), apresentaremos
              parte do conteúdo aprendido nesse semestre, combinando ciência, sabor e
              saúde.
            </p>

            <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
              Abordaremos os assuntos: ficha técnica, receitas preparadas durante as aulas
              e grupos alimentares, com destaque para leguminosas e carnes.
            </p>

            <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
              Antes de se aprofundar no mundo da TD, conheça um pouco sobre os
              elaboradores do projeto.
            </p>

            <div
              class="mt-12 flex flex-wrap justify-center md:justify-start items-center"
            >
              <a
                href="#participantes"
                class="text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-emerald-500 active:bg-emerald-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                Participantes
              </a>

              <a
                href="#ficha-tecnica"
                class="ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                Ficha Técnica
              </a>
            </div>
          </div>
        </div>
      </div>

      <img
        class="absolute top-0 b-auto right-0 pt-16 sm:w-6/12 -mt-48 sm:mt-0 w-10/12 max-h-860-px"
        :src="patternVue"
        alt="..."
      />
    </section>
    <section id="participantes" class="mt-48 md:mt-64 pb-40 relative bg-blueGray-100">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0)"
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
            class="text-blueGray-100 fill-current"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>
      <div class="container mx-auto">
        <div class="flex flex-wrap items-center">
          <div class="w-full md:w-6/12 lg:w-4/12 px-2 md:px-4 mr-auto ml-auto -mt-32">
            <div
              style="min-height: 535px"
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500"
            >
              <img
                alt="Ana Luiza Soares Lera"
                src="img-nutrition/analuiza.png"
                class="object-cover align-middle rounded-t-lg"
                style="height: 175px"
              />

              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-emerald-500 fill-current"
                  ></polygon>
                </svg>

                <h4 class="text-xl font-bold text-white">Ana Luiza Soares Lera</h4>

                <span class="text-sm text-emerald-100 font-semibold">
                  Integrante do projeto
                </span>

                <p class="text-md font-light mt-4 text-white leading-relaxed">
                  Tenho 19 anos e sou de Itapetininga - SP. Sempre gostei muito de
                  cozinhar e fico feliz em ter experiências práticas nas aulas de Técnica
                  e Dietética.
                </p>

                <p class="text-md font-light mt-2 text-white leading-relaxed">
                  Também adoro ler, ouvir música e conhecer lugares novos!
                </p>
              </blockquote>
            </div>
          </div>
          <div class="w-full md:w-6/12 lg:w-4/12 px-2 md:px-4 mr-auto ml-auto -mt-32">
            <div
              style="min-height: 535px"
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500"
            >
              <img
                alt="Júlia Gomes Brandão Clini"
                src="img-nutrition/juliagomes.png"
                class="object-cover align-middle rounded-t-lg"
                style="height: 175px"
              />

              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-emerald-500 fill-current"
                  ></polygon>
                </svg>

                <h4 class="text-xl font-bold text-white">Júlia Gomes Brandão Clini</h4>

                <span class="text-sm text-emerald-100 font-semibold">
                  Integrante do projeto
                </span>

                <p class="text-md font-light mt-4 text-white leading-relaxed">
                  Tenho 19 anos e sou de Jundiaí - SP. Estou me encantando cada dia mais
                  pelo hábito de cozinhar e provar coisas novas, principalmente com as
                  aulas práticas do curso de Nutrição. Gosto também de aproveitar a
                  companhia de quem amo e assistir séries.
                </p>
              </blockquote>
            </div>
          </div>
          <div class="w-full md:w-6/12 lg:w-4/12 px-2 md:px-4 mr-auto ml-auto -mt-32">
            <div
              style="min-height: 535px"
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500"
            >
              <img
                alt="Laís Bordini Mestriner"
                src="img-nutrition/lais.png"
                class="object-cover align-middle rounded-t-lg"
                style="height: 175px"
              />

              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-emerald-500 fill-current"
                  ></polygon>
                </svg>

                <h4 class="text-xl font-bold text-white">Laís Bordini Mestriner</h4>

                <span class="text-sm text-emerald-100 font-semibold">
                  Integrante do projeto
                </span>

                <p class="text-md font-light mt-4 text-white leading-relaxed">
                  Tenho 18 anos, sou de Jundiaí - SP. Gosto de usar meu tempo livre para
                  ler e assistir séries. Adoro cozinhar, principalmente receitas
                  diferentes no final de semana!
                </p>
              </blockquote>
            </div>
          </div>
          <div class="w-full md:w-6/12 lg:w-4/12 px-2 md:px-4 mr-auto ml-auto">
            <div
              style="min-height: 535px"
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500"
            >
              <img
                alt="Luana Domingos Casagrande"
                src="img-nutrition/luana.png"
                class="object-cover align-middle rounded-t-lg"
                style="height: 175px"
              />

              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-emerald-500 fill-current"
                  ></polygon>
                </svg>

                <h4 class="text-xl font-bold text-white">Luana Domingos Casagrande</h4>

                <span class="text-sm text-emerald-100 font-semibold">
                  Integrante do projeto
                </span>

                <p class="text-md font-light mt-4 text-white leading-relaxed">
                  Tenho 21 anos e sou de Rio Claro - SP. Gosto de cozinhar, principalmente
                  receitas doces, e amo muito ler livros.
                </p>
              </blockquote>
            </div>
          </div>
          <div class="w-full md:w-6/12 lg:w-4/12 px-2 md:px-4 mr-auto ml-auto">
            <div
              style="min-height: 535px"
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500"
            >
              <img
                alt="Léo Castro"
                src="img-nutrition/leo.png"
                class="object-cover align-middle rounded-t-lg"
                style="height: 175px"
              />

              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-emerald-500 fill-current"
                  ></polygon>
                </svg>

                <h4 class="text-xl font-bold text-white">Léo Castro</h4>

                <span class="text-sm text-emerald-100 font-semibold">
                  Integrante do projeto
                </span>

                <p class="text-md font-light mt-4 text-white leading-relaxed">
                  Leo Castro, estudante Unicamp Limeira - SP
                </p>
              </blockquote>
            </div>
          </div>
        </div>
      </div>

      <div class="container mx-auto overflow-hidden pb-20">
        <div class="flex flex-wrap items-center" id="ficha-tecnica">
          <!-- TEXTO -->
          <div class="w-full md:w-6/12 lg:w-5/12 px-12 md:px-4 ml-auto mr-auto mt-32">
            <div
              class="text-emerald-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
            >
              <i class="fas fa-utensils text-xl"></i>
            </div>

            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              Ficha Técnica de Preparo (FTP)
            </h3>

            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600">
              A Ficha Técnica de Preparo é o principal instrumento para garantir
              qualidade, padronização e controle de custos nas preparações. Mais do que
              uma receita, ela assegura que o prato final mantenha sabor, valor
              nutricional e viabilidade econômica.
            </p>

            <p class="text-lg font-light leading-relaxed mt-2 mb-6 text-blueGray-600">
              Com a FTP, reduzimos desperdícios, organizamos o processo produtivo e
              garantimos consistência em cada preparo.
            </p>

            <div class="block pb-6">
              <span
                class="text-xs font-semibold inline-block py-1 px-2 rounded-full text-blueGray-500 bg-white mr-2 mt-2"
              >
                Padronização
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 rounded-full text-blueGray-500 bg-white mr-2 mt-2"
              >
                Controle de custos
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 rounded-full text-blueGray-500 bg-white mr-2 mt-2"
              >
                Valor nutricional
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 rounded-full text-blueGray-500 bg-white mr-2 mt-2"
              >
                Redução de desperdício
              </span>
              <span
                class="text-xs font-semibold inline-block py-1 px-2 rounded-full text-blueGray-500 bg-white mr-2 mt-2"
              >
                Reprodutibilidade
              </span>
            </div>

            <!-- CTA MELHORADO -->
            <a
              href="/pdfs/ficha-tecnica.pdf"
              target="_blank"
              class="inline-block text-white font-bold px-6 py-3 rounded bg-emerald-500 hover:bg-emerald-600 shadow-lg transition-all duration-150"
            >
              Saber mais sobre ficha técnica
              <i class="fa fa-file-pdf ml-2"></i>
            </a>
          </div>
        </div>
      </div>

   

      <!-- <div class="justify-center text-center flex flex-wrap mt-24">
        <div class="w-full md:w-6/12 px-12 md:px-4">
          <h2 class="font-semibold text-4xl">Beautiful Example Pages</h2>
          <p class="text-lg leading-relaxed mt-4 mb-4 text-blueGray-500">
            Vue Notus is a completly new product built using our past experience in web
            templates. Take the examples we made for you and start playing with them.
          </p>
        </div>
      </div> -->
    </section>

    <!-- <section class="block relative z-1 bg-blueGray-600">
      <div class="container mx-auto">
        <div class="justify-center flex flex-wrap">
          <div class="w-full lg:w-12/12 px-4 -mt-24">
            <div class="flex flex-wrap">
              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">Login Page</h5>
                <router-link to="/auth/login">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="login"
                    />
                  </div>
                </router-link>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">Profile Page</h5>
                <router-link to="/profile">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="profile"
                    />
                  </div>
                </router-link>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">Landing Page</h5>
                <router-link to="/landing">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="landing"
                    />
                  </div>
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section> -->

    <!-- <section class="py-20 bg-blueGray-600 overflow-hidden">
      <div class="container mx-auto pb-64">
        <div class="flex flex-wrap justify-center">
          <div class="w-full md:w-5/12 px-12 md:px-4 ml-auto mr-auto md:mt-64">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
            >
              <i class="fas fa-code-branch text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal text-white">
              Open Source
            </h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-400">
              Since
              <a
                href="https://tailwindcss.com/?ref=creativetim"
                class="text-blueGray-300"
                target="_blank"
              >
                Tailwind CSS
              </a>
              is an open source project we wanted to continue this movement too. You can
              give this version a try to feel the design and also test the quality of the
              code!
            </p>
            <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-400">
              Get it free on Github and please help us spread the news with a Star!
            </p>
            <a
              href="https://github.com/creativetimofficial/vue-notus?ref=vn-index"
              target="_blank"
              class="github-star mt-4 inline-block text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
            >
              Github Star
            </a>
          </div>

          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto mt-32 relative">
            <i
              class="fab fa-github text-blueGray-700 text-55 absolute -top-150-px -right-100 left-auto opacity-80"
            ></i>
          </div>
        </div>
      </div>
    </section> -->

    <section class="pb-16 bg-blueGray-200 relative pt-32">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0)"
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

     <div class="container mx-auto">
  <div
    class="flex flex-wrap justify-center bg-white shadow-xl rounded-lg -mt-64 py-16 px-12 relative z-10"
  >
    <div class="w-full text-center lg:w-8/12">

      <p class="text-4xl text-center">
        <span role="img" aria-label="food"> 🍽️ </span>
      </p>

      <h3 class="font-semibold text-3xl">
        Ciência, prática e alimentação de qualidade
      </h3>

      <p class="text-blueGray-500 text-lg leading-relaxed mt-4 mb-4">
        Este projeto representa a união entre teoria e prática na formação em Nutrição,
        demonstrando como o conhecimento científico pode ser aplicado no dia a dia
        das preparações alimentares.
      </p>

      <p class="text-blueGray-500 text-lg leading-relaxed mt-2 mb-6">
        Através da Técnica e Dietética, buscamos desenvolver não apenas habilidades
        culinárias, mas também um olhar crítico sobre qualidade, custo, saúde e
        sustentabilidade na alimentação.
      </p>

      <div class="sm:block flex flex-col mt-10">
        <a
          href="#participantes"
          class="text-white font-bold px-6 py-4 rounded mr-1 mb-2 bg-emerald-500 hover:bg-emerald-600 uppercase text-sm shadow transition-all duration-150"
        >
          Conhecer Integrantes
        </a>

        <a
          href="/pdfs/ficha-tecnica.pdf"
          target="_blank"
          class="sm:ml-1 text-white font-bold px-6 py-4 rounded mr-1 mb-1 bg-blueGray-700 hover:bg-blueGray-600 uppercase text-sm shadow transition-all duration-150"
        >
          Ver Ficha Técnica
        </a>
      </div>

    </div>
  </div>
</div>
    </section>
    <footer-component />
  </div>
</template>
<script>
import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

import patternVue from "@/assets/img/pattern_vue.png";
import componentBtn from "@/assets/img/component-btn.png";
import componentProfileCard from "@/assets/img/component-profile-card.png";
import componentInfoCard from "@/assets/img/component-info-card.png";
import componentInfo2 from "@/assets/img/component-info-2.png";
import componentMenu from "@/assets/img/component-menu.png";
import componentBtnPink from "@/assets/img/component-btn-pink.png";
import documentation from "@/assets/img/documentation.png";
import login from "@/assets/img/login.jpg";
import profile from "@/assets/img/profile.jpg";
import landing from "@/assets/img/landing.jpg";

export default {
  data() {
    return {
      patternVue,
      componentBtn,
      componentProfileCard,
      componentInfoCard,
      componentInfo2,
      componentMenu,
      componentBtnPink,
      documentation,
      login,
      profile,
      landing,
    };
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
};
</script>
