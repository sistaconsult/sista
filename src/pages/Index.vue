<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight co mt-10">Bureau d’études SISTA </div>

        <div class="text-xl co">(Systèmes d’informations et Statistiques)</div>
      </div>
      <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
        <g-image height="70%" src="../../static/undraw_dashboard_nklg.svg" alt="hero" class="mx-auto sm:mx-5" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">
        Chez SISTA, nos objectifs sont d’améliorer l’efficacité de la collecte, de la validation, du traitement, du
        stockage et de la diffusion de données et de métadonnées; améliorer la qualité,et améliorer l'accessibilité et
        la visibilité des produits statistiques des l'organisations.
      </p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/undraw_operating_system_4lr6.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/undraw_programming_2svr.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Voici quelques projets réalisés par notre équipe:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>E-commerce</div>
            <div class="text-lg text-gray-600">
              Conception et développement d'une plate-forme de commerce électronique multi-vendeurs.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Gestion de scolarité.</div>
            <div class="text-lg text-gray-600">
              Développement d’une application pour la gestion de scolarité , implémenter sous forme
              d’un site web avec le Framework Django.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Analyse des sentiments pour les tweets.</div>
            <div class="text-lg text-gray-600">
              Une approche basé sur les réseaux de neurones pour la classification des sentiments,
              implémenter sous forme d’un site web avec le Framework Django avec keras, tensorflow.</div>
          </li>
        </ul>
      </div> <!-- end projects -->
    </div>
    <section class="container py-20">
      <div class="lg:w-2/3 md:3/4 mx-auto mb-10">
        <h1 class="font-heading font-semibold text-5xl text-center tracking-sm mb-4">Que faisons nous?</h1>
        <p class="text-xl text-grey text-center leading-normal">
          We create functional and intuitive applications for both desktop and mobile platform. While designing an
          application, we combine best practices for UI &amp; UX which helps your business to connect with the target
          audience.
          Nous créons des applications fonctionnelles et intuitives pour les plates-formes de bureau et mobiles. Lors de la conception d’une application, nous combinons les meilleures pratiques pour l'IU &amp; XU qui aide votre entreprise à se connecter avec le public cible.
        </p>
      </div>
      <div class="md:flex items-center py-10">
        <div class="md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:ml-auto md:mx-0 mx-auto"><img
              src="../../static/website-development.svg" alt="website-development"></div>
        </div>
        <div class="md:w-1/2 md:px-6 lg:pr-12">
          <div class="mb-4 text-center md:text-left">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Développement de site Web</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">
              Nous utilisons les dernières technologies telles que <a href="" rel="nofollow" title="Django"
                class="text-grey">Django</a> &amp; <a href="https://vuejs.org" rel="nofollow" title="Vue.js"
                class="text-grey">Vue.js</a> pour créer des applications Web pour votre entreprise.
            </p>
          </div>
          <div class="text-lg text-grey text-left md:pl-0 pl-6">
            <div class="flex items-center mb-3"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications Web personnalisées</span></div>
            <div class="flex items-center mb-3"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications E-Commerces</span></div>
 
          </div>
        </div>
      </div>
      <div class="md:flex items-center py-10">
        <div class="md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:ml-auto md:mx-0 mx-auto"><img
              src="../../static/mobile-application.svg" alt="mobile-application"></div>
        </div>
        <div class="md:w-1/2 md:px-6 lg:pr-12">
          <div class="mb-4 text-center md:text-left">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Applications mobiles</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">
              Besoin de développer une application mobile? Nous utilisons VueJS pour créer des applications mobiles multiplateformes PWA.
            </p>
          </div>
          <div class="text-lg text-grey md:pl-0 pl-6">
            <div class="flex items-center mb-3"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications Android</span></div>
            <div class="flex items-center mb-3"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications iOS</span></div>
          </div>
        </div>
      </div>
      <div class="md:flex items-center py-10">
        <div class="md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:ml-auto md:mx-0 mx-auto"><img src="../../static/desktop-software.svg"
              alt="desktop-software"></div>
        </div>
        <div class="md:w-1/2 md:px-6 lg:pr-12">
          <div class="mb-4 text-center md:text-left">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Logiciel de bureau</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">
             Avec l'aide de Electron.js, nous pouvons également vous aider à développer un un logiciel de bureau.
            </p>
          </div>
          <div class="text-lg text-grey md:pl-0 pl-6">
            <div class="flex items-center mb-3"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications MacOS</span></div>
            <div class="flex items-center mb-3"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications Windows</span></div>
            <div class="flex items-center"><svg viewBox="0 0 20 19" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
                <g fill="none" fill-rule="evenodd">
                  <ellipse fill="#F0F2FF" cx="10" cy="9.4" rx="9.5" ry="9.4"></ellipse>
                  <path fill="#6C63FF" d="M4.5 9.7l1.1-1.2 2.8 3 6-6.6 1.1 1.2-7.2 7.7z"></path>
                </g>
              </svg> <span class="ml-3">Applications Ubuntu/Linux</span></div>
          </div>
        </div>
      </div>
    </section>
    <section class="container">
      <div class="lg:w-2/3 md:3/4 mx-auto mb-10">
        <h1 class="font-heading font-semibold text-5xl text-center tracking-sm mb-4">Notre processus</h1>
        <p class="text-xl text-grey text-center leading-normal">
          Convertir une idée en un produit réel nécessite une approche disciplinée. Chaque projet de Chitranu Technologies suit notre processus de réflexion afin que le produit final permette l'équilibre entre qualité et évolutivité.
          </p>
      </div>
      <div class="flex flex-wrap-reverse items-center py-10">
        <div class="text-centre w-full md:w-1/2 md:px-6">
          <div class="text-center xl:w-3/4 md:w-full md:w-2/3 md:ml-auto md:mx-0 mx-auto">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Recherche et planification</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">
              Avant de commencer à travailler sur le projet, nous effectuons des recherches et une planification appropriées. C'est un processus de brainstorming qui nous aide à trouver les besoins et les exigences du projet.
              </p>
          </div>
        </div>
        <div class="w-full md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:mr-auto md:mx-0 mx-auto"><img
              src="../../static/reasearch-&amp;-planning.svg" alt="reasearch-&amp;-planning"></div>
        </div>
      </div>
      <div class="text-center my-5 hidden md:flex justify-center"><svg width="454px" height="166px"
          viewBox="0 0 454 166" version="1.1" xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.5">
            <g transform="translate(-974.000000, -4888.000000)" fill="#979797" fill-rule="nonzero">
              <path
                d="M1421.30162,5048.07776 L1426.18004,5039.405 L1427.92319,5040.38552 L1421.17319,5052.38552 L1420.30162,5053.93499 L1419.43004,5052.38552 L1412.68004,5040.38552 L1414.42319,5039.405 L1419.30162,5048.07776 L1419.30162,5039.89526 L1419.30162,5038.39776 L1421.30162,5038.39776 L1421.30162,5039.89526 L1421.30162,5048.07776 Z M974,4888 L976,4888 L976,4900 L974,4900 L974,4888 Z M974,4912 L976,4912 L976,4924 L974,4924 L974,4912 Z M974,4936 L976,4936 L976,4942.5515 C976,4944.30448 976.23722,4946.02511 976.700112,4947.68026 L974.774017,4948.21892 C974.262203,4946.38884 974,4944.48701 974,4942.5515 L974,4936 Z M981.562855,4958.69043 L982.843345,4957.15409 C985.782933,4959.60414 989.391444,4961.11985 993.25127,4961.47202 L993.069546,4963.46375 C988.802404,4963.07442 984.811533,4961.3981 981.562855,4958.69043 Z M1005.22282,4963.60589 L1005.23341,4961.60592 L1017.23324,4961.66943 L1017.22266,4963.6694 L1005.22282,4963.60589 Z M1029.22249,4963.73291 L1029.23307,4961.73294 L1041.2329,4961.79644 L1041.22232,4963.79642 L1029.22249,4963.73291 Z M1053.22215,4963.85992 L1053.23274,4961.85995 L1065.23257,4961.92346 L1065.22198,4963.92343 L1053.22215,4963.85992 Z M1077.22182,4963.98694 L1077.2324,4961.98696 L1089.23223,4962.05047 L1089.22165,4964.05044 L1077.22182,4963.98694 Z M1101.22148,4964.11395 L1101.23206,4962.11398 L1113.2319,4962.17748 L1113.22131,4964.17746 L1101.22148,4964.11395 Z M1125.22114,4964.24096 L1125.23173,4962.24099 L1137.23156,4962.3045 L1137.22098,4964.30447 L1125.22114,4964.24096 Z M1149.22081,4964.36798 L1149.23139,4962.368 L1161.23122,4962.43151 L1161.22064,4964.43148 L1149.22081,4964.36798 Z M1173.22047,4964.49499 L1173.23106,4962.49502 L1185.23089,4962.55853 L1185.2203,4964.5585 L1173.22047,4964.49499 Z M1197.22014,4964.622 L1197.23072,4962.62203 L1209.23055,4962.68554 L1209.21997,4964.68551 L1197.22014,4964.622 Z M1221.2198,4964.74902 L1221.23038,4962.74905 L1233.23022,4962.81255 L1233.21963,4964.81252 L1221.2198,4964.74902 Z M1245.21946,4964.87603 L1245.23005,4962.87606 L1257.22988,4962.93957 L1257.2193,4964.93954 L1245.21946,4964.87603 Z M1269.21913,4965.00305 L1269.22971,4963.00307 L1281.22954,4963.06658 L1281.21896,4965.06655 L1269.21913,4965.00305 Z M1293.21879,4965.13006 L1293.22938,4963.13009 L1305.22921,4963.19359 L1305.21862,4965.19357 L1293.21879,4965.13006 Z M1317.21846,4965.25707 L1317.22904,4963.2571 L1329.22887,4963.32061 L1329.21829,4965.32058 L1317.21846,4965.25707 Z M1341.21812,4965.38409 L1341.2287,4963.38411 L1353.22854,4963.44762 L1353.21795,4965.44759 L1341.21812,4965.38409 Z M1365.21778,4965.5111 L1365.22837,4963.51113 L1377.2282,4963.57463 L1377.21761,4965.57461 L1365.21778,4965.5111 Z M1389.21745,4965.63811 L1389.22803,4963.63814 L1400.41276,4963.69733 C1400.69851,4963.69885 1400.98359,4963.70607 1401.26788,4963.71898 L1401.17717,4965.71692 C1400.91957,4965.70522 1400.6612,4965.69868 1400.40217,4965.69731 L1389.21745,4965.63811 Z M1411.78093,4969.55545 L1412.99046,4967.96264 C1416.36727,4970.52688 1418.90641,4974.0594 1420.24165,4978.09261 L1418.34299,4978.72118 C1417.13537,4975.07343 1414.83738,4971.87642 1411.78093,4969.55545 Z M1419.30162,4990.39776 L1421.30162,4990.39776 L1421.30162,5002.39776 L1419.30162,5002.39776 L1419.30162,4990.39776 Z M1419.30162,5014.39776 L1421.30162,5014.39776 L1421.30162,5026.39776 L1419.30162,5026.39776 L1419.30162,5014.39776 Z">
              </path>
            </g>
          </g>
        </svg></div>
      <div class="text-center my-5 md:hidden"><svg width="16px" height="74px" viewBox="0 0 16 74" version="1.1"
          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.499627976">
            <g transform="translate(-377.000000, -6231.000000)" fill="#979797" fill-rule="nonzero">
              <g transform="translate(122.000000, 679.000000)">
                <g transform="translate(37.000000, 2110.000000)">
                  <path
                    d="M226.009082,3511.7103 L231.960955,3501.30143 L233.697157,3502.2942 L226.86282,3514.24637 L225.980355,3515.78966 L225.119712,3514.23409 L218.454384,3502.18686 L220.204397,3501.21863 L226.009082,3511.7103 Z M225.500025,3441.99296 L227.499975,3442.00704 L227.408428,3455.00672 L225.408478,3454.99264 L225.500025,3441.99296 Z M225.316931,3467.99231 L227.316881,3468.0064 L227.225334,3481.00608 L225.225384,3480.99199 L225.316931,3467.99231 Z M225.133837,3493.99167 L227.133787,3494.00575 L227.079127,3501.76746 L227.04224,3507.00543 L225.04229,3506.99135 L225.079177,3501.75338 L225.133837,3493.99167 Z">
                  </path>
                </g>
              </g>
            </g>
          </g>
        </svg></div>
      <div class="flex flex-wrap md:flex items-center py-10">
        <div class="w-full md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:ml-auto md:mx-0 mx-auto"><img src="../../static/design.svg"
              alt="design"></div>
        </div>
        <div class="w-full md:w-1/2 md:px-6">
          <div class="text-center xl:w-3/4 md:w-full md:w-2/3 md:mr-auto md:mx-0 mx-auto">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Design</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">
              Nous combinons les meilleures pratiques UI / UX pour créer un design fonctionnel. Nous construisons un guide de style simple en un système de design utilisable par nos développeurs.
              </p>
          </div>
        </div>
      </div>
      <div class="text-center my-5 hidden md:flex justify-center"><svg width="448px" height="198px"
          viewBox="0 0 448 198" version="1.1" xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.5">
            <g transform="translate(-791.000000, -4452.000000)" fill="#979797" fill-rule="nonzero">
              <path
                d="M799,4645.71027 L804.878424,4635.25974 L806.621576,4636.24026 L799.871576,4648.24026 L799,4649.78973 L798.128424,4648.24026 L791.378424,4636.24026 L793.121576,4635.25974 L799,4645.71027 Z M1236.20082,4452 L1238.20082,4452 L1238.20082,4465 L1236.20082,4465 L1236.20082,4452 Z M1236.20082,4478 L1238.20082,4478 L1238.20082,4491 L1236.20082,4491 L1236.20082,4478 Z M1236.20082,4504 L1238.20082,4504 L1238.20082,4517 L1236.20082,4517 L1236.20082,4504 Z M1234.32593,4529.28712 L1236.12749,4530.15567 C1234.12862,4534.30174 1230.8068,4537.69284 1226.70406,4539.7782 L1225.79784,4537.9953 C1229.51016,4536.10837 1232.51737,4533.03845 1234.32593,4529.28712 Z M1213.46439,4540.05553 L1213.46907,4542.05553 L1200.46911,4542.08594 L1200.46443,4540.08595 L1213.46439,4540.05553 Z M1187.46447,4540.11636 L1187.46914,4542.11636 L1174.46918,4542.14677 L1174.4645,4540.14678 L1187.46447,4540.11636 Z M1161.46454,4540.17719 L1161.46922,4542.17719 L1148.46925,4542.2076 L1148.46457,4540.20761 L1161.46454,4540.17719 Z M1135.46461,4540.23802 L1135.46929,4542.23802 L1122.46932,4542.26843 L1122.46464,4540.26844 L1135.46461,4540.23802 Z M1109.46468,4540.29886 L1109.46936,4542.29885 L1096.46939,4542.32927 L1096.46471,4540.32927 L1109.46468,4540.29886 Z M1083.46475,4540.35969 L1083.46943,4542.35968 L1070.46947,4542.3901 L1070.46479,4540.3901 L1083.46475,4540.35969 Z M1057.46482,4540.42052 L1057.4695,4542.42051 L1044.46954,4542.45093 L1044.46486,4540.45093 L1057.46482,4540.42052 Z M1031.46489,4540.48135 L1031.46957,4542.48134 L1018.46961,4542.51176 L1018.46493,4540.51176 L1031.46489,4540.48135 Z M1005.46496,4540.54218 L1005.46964,4542.54217 L992.469679,4542.57259 L992.464999,4540.57259 L1005.46496,4540.54218 Z M979.465035,4540.60301 L979.469714,4542.603 L966.46975,4542.63342 L966.465071,4540.63342 L979.465035,4540.60301 Z M953.465106,4540.66384 L953.469785,4542.66383 L940.469821,4542.69425 L940.465142,4540.69426 L953.465106,4540.66384 Z M927.465177,4540.72467 L927.469857,4542.72467 L914.469892,4542.75508 L914.465213,4540.75509 L927.465177,4540.72467 Z M901.465248,4540.7855 L901.469928,4542.7855 L888.469963,4542.81591 L888.465284,4540.81592 L901.465248,4540.7855 Z M875.46532,4540.84633 L875.469999,4542.84633 L862.470035,4542.87674 L862.465355,4540.87675 L875.46532,4540.84633 Z M849.465391,4540.90716 L849.47007,4542.90716 L836.470106,4542.93757 L836.465426,4540.93758 L849.465391,4540.90716 Z M823.465462,4540.96799 L823.470141,4542.96799 L818.955547,4542.97855 C816.199591,4542.985 813.529548,4543.57784 811.080745,4544.70225 L810.246189,4542.88469 C812.954069,4541.64133 815.906968,4540.98568 818.950867,4540.97856 L823.465462,4540.96799 Z M800.478279,4552.07352 L802.241148,4553.01814 C800.793374,4555.72003 800.017381,4558.73932 800.000304,4561.86718 L800,4565.29161 L798,4565.29143 L798.000319,4561.86164 C798.019199,4558.4005 798.877501,4555.06095 800.478279,4552.07352 Z M798,4578.29152 L800,4578.29152 L800,4591.29152 L798,4591.29152 L798,4578.29152 Z M798,4604.29152 L800,4604.29152 L800,4617.29152 L798,4617.29152 L798,4604.29152 Z M798,4630.29152 L800,4630.29152 L800,4635.75 L800,4643.29152 L798,4643.29152 L798,4635.75 L798,4630.29152 Z">
              </path>
            </g>
          </g>
        </svg></div>
      <div class="text-center my-5 md:hidden"><svg width="16px" height="74px" viewBox="0 0 16 74" version="1.1"
          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.499627976">
            <g transform="translate(-377.000000, -6231.000000)" fill="#979797" fill-rule="nonzero">
              <g transform="translate(122.000000, 679.000000)">
                <g transform="translate(37.000000, 2110.000000)">
                  <path
                    d="M226.009082,3511.7103 L231.960955,3501.30143 L233.697157,3502.2942 L226.86282,3514.24637 L225.980355,3515.78966 L225.119712,3514.23409 L218.454384,3502.18686 L220.204397,3501.21863 L226.009082,3511.7103 Z M225.500025,3441.99296 L227.499975,3442.00704 L227.408428,3455.00672 L225.408478,3454.99264 L225.500025,3441.99296 Z M225.316931,3467.99231 L227.316881,3468.0064 L227.225334,3481.00608 L225.225384,3480.99199 L225.316931,3467.99231 Z M225.133837,3493.99167 L227.133787,3494.00575 L227.079127,3501.76746 L227.04224,3507.00543 L225.04229,3506.99135 L225.079177,3501.75338 L225.133837,3493.99167 Z">
                  </path>
                </g>
              </g>
            </g>
          </g>
        </svg></div>
      <div class="flex flex-wrap-reverse items-center py-10">
        <div class="text-centre w-full md:w-1/2 md:px-6">
          <div class="text-center xl:w-3/4 md:w-full md:w-2/3 md:ml-auto md:mx-0 mx-auto">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Développement</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">Un code propre et une structure de code qualité sont nos racines solides. Et en utilisant des approches telles que le modèle architectural OOP et MVC, nous garantissons l’évolutivité de l’application.</p>
          </div>
        </div>
        <div class="w-full md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:mr-auto md:mx-0 mx-auto"><img src="../../static/development.svg"
              alt="development"></div>
        </div>
      </div>
      <div class="text-center my-5 hidden md:flex justify-center"><svg width="454px" height="166px"
          viewBox="0 0 454 166" version="1.1" xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.5">
            <g transform="translate(-974.000000, -4888.000000)" fill="#979797" fill-rule="nonzero">
              <path
                d="M1421.30162,5048.07776 L1426.18004,5039.405 L1427.92319,5040.38552 L1421.17319,5052.38552 L1420.30162,5053.93499 L1419.43004,5052.38552 L1412.68004,5040.38552 L1414.42319,5039.405 L1419.30162,5048.07776 L1419.30162,5039.89526 L1419.30162,5038.39776 L1421.30162,5038.39776 L1421.30162,5039.89526 L1421.30162,5048.07776 Z M974,4888 L976,4888 L976,4900 L974,4900 L974,4888 Z M974,4912 L976,4912 L976,4924 L974,4924 L974,4912 Z M974,4936 L976,4936 L976,4942.5515 C976,4944.30448 976.23722,4946.02511 976.700112,4947.68026 L974.774017,4948.21892 C974.262203,4946.38884 974,4944.48701 974,4942.5515 L974,4936 Z M981.562855,4958.69043 L982.843345,4957.15409 C985.782933,4959.60414 989.391444,4961.11985 993.25127,4961.47202 L993.069546,4963.46375 C988.802404,4963.07442 984.811533,4961.3981 981.562855,4958.69043 Z M1005.22282,4963.60589 L1005.23341,4961.60592 L1017.23324,4961.66943 L1017.22266,4963.6694 L1005.22282,4963.60589 Z M1029.22249,4963.73291 L1029.23307,4961.73294 L1041.2329,4961.79644 L1041.22232,4963.79642 L1029.22249,4963.73291 Z M1053.22215,4963.85992 L1053.23274,4961.85995 L1065.23257,4961.92346 L1065.22198,4963.92343 L1053.22215,4963.85992 Z M1077.22182,4963.98694 L1077.2324,4961.98696 L1089.23223,4962.05047 L1089.22165,4964.05044 L1077.22182,4963.98694 Z M1101.22148,4964.11395 L1101.23206,4962.11398 L1113.2319,4962.17748 L1113.22131,4964.17746 L1101.22148,4964.11395 Z M1125.22114,4964.24096 L1125.23173,4962.24099 L1137.23156,4962.3045 L1137.22098,4964.30447 L1125.22114,4964.24096 Z M1149.22081,4964.36798 L1149.23139,4962.368 L1161.23122,4962.43151 L1161.22064,4964.43148 L1149.22081,4964.36798 Z M1173.22047,4964.49499 L1173.23106,4962.49502 L1185.23089,4962.55853 L1185.2203,4964.5585 L1173.22047,4964.49499 Z M1197.22014,4964.622 L1197.23072,4962.62203 L1209.23055,4962.68554 L1209.21997,4964.68551 L1197.22014,4964.622 Z M1221.2198,4964.74902 L1221.23038,4962.74905 L1233.23022,4962.81255 L1233.21963,4964.81252 L1221.2198,4964.74902 Z M1245.21946,4964.87603 L1245.23005,4962.87606 L1257.22988,4962.93957 L1257.2193,4964.93954 L1245.21946,4964.87603 Z M1269.21913,4965.00305 L1269.22971,4963.00307 L1281.22954,4963.06658 L1281.21896,4965.06655 L1269.21913,4965.00305 Z M1293.21879,4965.13006 L1293.22938,4963.13009 L1305.22921,4963.19359 L1305.21862,4965.19357 L1293.21879,4965.13006 Z M1317.21846,4965.25707 L1317.22904,4963.2571 L1329.22887,4963.32061 L1329.21829,4965.32058 L1317.21846,4965.25707 Z M1341.21812,4965.38409 L1341.2287,4963.38411 L1353.22854,4963.44762 L1353.21795,4965.44759 L1341.21812,4965.38409 Z M1365.21778,4965.5111 L1365.22837,4963.51113 L1377.2282,4963.57463 L1377.21761,4965.57461 L1365.21778,4965.5111 Z M1389.21745,4965.63811 L1389.22803,4963.63814 L1400.41276,4963.69733 C1400.69851,4963.69885 1400.98359,4963.70607 1401.26788,4963.71898 L1401.17717,4965.71692 C1400.91957,4965.70522 1400.6612,4965.69868 1400.40217,4965.69731 L1389.21745,4965.63811 Z M1411.78093,4969.55545 L1412.99046,4967.96264 C1416.36727,4970.52688 1418.90641,4974.0594 1420.24165,4978.09261 L1418.34299,4978.72118 C1417.13537,4975.07343 1414.83738,4971.87642 1411.78093,4969.55545 Z M1419.30162,4990.39776 L1421.30162,4990.39776 L1421.30162,5002.39776 L1419.30162,5002.39776 L1419.30162,4990.39776 Z M1419.30162,5014.39776 L1421.30162,5014.39776 L1421.30162,5026.39776 L1419.30162,5026.39776 L1419.30162,5014.39776 Z">
              </path>
            </g>
          </g>
        </svg></div>
      <div class="text-center my-5 md:hidden"><svg width="16px" height="74px" viewBox="0 0 16 74" version="1.1"
          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.499627976">
            <g transform="translate(-377.000000, -6231.000000)" fill="#979797" fill-rule="nonzero">
              <g transform="translate(122.000000, 679.000000)">
                <g transform="translate(37.000000, 2110.000000)">
                  <path
                    d="M226.009082,3511.7103 L231.960955,3501.30143 L233.697157,3502.2942 L226.86282,3514.24637 L225.980355,3515.78966 L225.119712,3514.23409 L218.454384,3502.18686 L220.204397,3501.21863 L226.009082,3511.7103 Z M225.500025,3441.99296 L227.499975,3442.00704 L227.408428,3455.00672 L225.408478,3454.99264 L225.500025,3441.99296 Z M225.316931,3467.99231 L227.316881,3468.0064 L227.225334,3481.00608 L225.225384,3480.99199 L225.316931,3467.99231 Z M225.133837,3493.99167 L227.133787,3494.00575 L227.079127,3501.76746 L227.04224,3507.00543 L225.04229,3506.99135 L225.079177,3501.75338 L225.133837,3493.99167 Z">
                  </path>
                </g>
              </g>
            </g>
          </g>
        </svg></div>
      <div class="md:flex items-center py-10">
        <div class="w-full md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:ml-auto md:mx-0 mx-auto"><img src="../../static/testing.svg"
              alt="testing"></div>
        </div>
        <div class="w-full md:w-1/2 md:px-6">
          <div class="text-center xl:w-3/4 md:w-full md:w-2/3 md:mr-auto md:mx-0 mx-auto">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Test</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">
              Nous utilisons une approche de développement piloté par les tests (<a
                href="https://en.wikipedia.org/wiki/Test-driven_development" rel="nofollow"
                title="Test-driven development" class="text-grey">TDD</a>) lors de la construction du produit. Ensemble, nous veillons à ce que l'application finale fonctionne parfaitement sur la plupart des appareils.
              </p>
          </div>
        </div>
      </div>
      <div class="text-center my-5 hidden md:flex justify-center"><svg width="448px" height="198px"
          viewBox="0 0 448 198" version="1.1" xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.5">
            <g transform="translate(-791.000000, -4452.000000)" fill="#979797" fill-rule="nonzero">
              <path
                d="M799,4645.71027 L804.878424,4635.25974 L806.621576,4636.24026 L799.871576,4648.24026 L799,4649.78973 L798.128424,4648.24026 L791.378424,4636.24026 L793.121576,4635.25974 L799,4645.71027 Z M1236.20082,4452 L1238.20082,4452 L1238.20082,4465 L1236.20082,4465 L1236.20082,4452 Z M1236.20082,4478 L1238.20082,4478 L1238.20082,4491 L1236.20082,4491 L1236.20082,4478 Z M1236.20082,4504 L1238.20082,4504 L1238.20082,4517 L1236.20082,4517 L1236.20082,4504 Z M1234.32593,4529.28712 L1236.12749,4530.15567 C1234.12862,4534.30174 1230.8068,4537.69284 1226.70406,4539.7782 L1225.79784,4537.9953 C1229.51016,4536.10837 1232.51737,4533.03845 1234.32593,4529.28712 Z M1213.46439,4540.05553 L1213.46907,4542.05553 L1200.46911,4542.08594 L1200.46443,4540.08595 L1213.46439,4540.05553 Z M1187.46447,4540.11636 L1187.46914,4542.11636 L1174.46918,4542.14677 L1174.4645,4540.14678 L1187.46447,4540.11636 Z M1161.46454,4540.17719 L1161.46922,4542.17719 L1148.46925,4542.2076 L1148.46457,4540.20761 L1161.46454,4540.17719 Z M1135.46461,4540.23802 L1135.46929,4542.23802 L1122.46932,4542.26843 L1122.46464,4540.26844 L1135.46461,4540.23802 Z M1109.46468,4540.29886 L1109.46936,4542.29885 L1096.46939,4542.32927 L1096.46471,4540.32927 L1109.46468,4540.29886 Z M1083.46475,4540.35969 L1083.46943,4542.35968 L1070.46947,4542.3901 L1070.46479,4540.3901 L1083.46475,4540.35969 Z M1057.46482,4540.42052 L1057.4695,4542.42051 L1044.46954,4542.45093 L1044.46486,4540.45093 L1057.46482,4540.42052 Z M1031.46489,4540.48135 L1031.46957,4542.48134 L1018.46961,4542.51176 L1018.46493,4540.51176 L1031.46489,4540.48135 Z M1005.46496,4540.54218 L1005.46964,4542.54217 L992.469679,4542.57259 L992.464999,4540.57259 L1005.46496,4540.54218 Z M979.465035,4540.60301 L979.469714,4542.603 L966.46975,4542.63342 L966.465071,4540.63342 L979.465035,4540.60301 Z M953.465106,4540.66384 L953.469785,4542.66383 L940.469821,4542.69425 L940.465142,4540.69426 L953.465106,4540.66384 Z M927.465177,4540.72467 L927.469857,4542.72467 L914.469892,4542.75508 L914.465213,4540.75509 L927.465177,4540.72467 Z M901.465248,4540.7855 L901.469928,4542.7855 L888.469963,4542.81591 L888.465284,4540.81592 L901.465248,4540.7855 Z M875.46532,4540.84633 L875.469999,4542.84633 L862.470035,4542.87674 L862.465355,4540.87675 L875.46532,4540.84633 Z M849.465391,4540.90716 L849.47007,4542.90716 L836.470106,4542.93757 L836.465426,4540.93758 L849.465391,4540.90716 Z M823.465462,4540.96799 L823.470141,4542.96799 L818.955547,4542.97855 C816.199591,4542.985 813.529548,4543.57784 811.080745,4544.70225 L810.246189,4542.88469 C812.954069,4541.64133 815.906968,4540.98568 818.950867,4540.97856 L823.465462,4540.96799 Z M800.478279,4552.07352 L802.241148,4553.01814 C800.793374,4555.72003 800.017381,4558.73932 800.000304,4561.86718 L800,4565.29161 L798,4565.29143 L798.000319,4561.86164 C798.019199,4558.4005 798.877501,4555.06095 800.478279,4552.07352 Z M798,4578.29152 L800,4578.29152 L800,4591.29152 L798,4591.29152 L798,4578.29152 Z M798,4604.29152 L800,4604.29152 L800,4617.29152 L798,4617.29152 L798,4604.29152 Z M798,4630.29152 L800,4630.29152 L800,4635.75 L800,4643.29152 L798,4643.29152 L798,4635.75 L798,4630.29152 Z">
              </path>
            </g>
          </g>
        </svg></div>
      <div class="text-center my-5 md:hidden"><svg width="16px" height="74px" viewBox="0 0 16 74" version="1.1"
          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.499627976">
            <g transform="translate(-377.000000, -6231.000000)" fill="#979797" fill-rule="nonzero">
              <g transform="translate(122.000000, 679.000000)">
                <g transform="translate(37.000000, 2110.000000)">
                  <path
                    d="M226.009082,3511.7103 L231.960955,3501.30143 L233.697157,3502.2942 L226.86282,3514.24637 L225.980355,3515.78966 L225.119712,3514.23409 L218.454384,3502.18686 L220.204397,3501.21863 L226.009082,3511.7103 Z M225.500025,3441.99296 L227.499975,3442.00704 L227.408428,3455.00672 L225.408478,3454.99264 L225.500025,3441.99296 Z M225.316931,3467.99231 L227.316881,3468.0064 L227.225334,3481.00608 L225.225384,3480.99199 L225.316931,3467.99231 Z M225.133837,3493.99167 L227.133787,3494.00575 L227.079127,3501.76746 L227.04224,3507.00543 L225.04229,3506.99135 L225.079177,3501.75338 L225.133837,3493.99167 Z">
                  </path>
                </g>
              </g>
            </g>
          </g>
        </svg></div>
      <div class="flex flex-wrap-reverse items-center py-10">
        <div class="text-centre w-full md:w-1/2 md:px-6">
          <div class="text-center xl:w-3/4 md:w-full md:w-2/3 md:ml-auto md:mx-0 mx-auto">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Lancement</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">Lors du lancement, nous suivons le processus simplifié de déploiement de Git et Docker, ce qui vous assure un lancement en douceur et avec succès.</p>
          </div>
        </div>
        <div class="w-full md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:mr-auto md:mx-0 mx-auto"><img src="../../static/launching.svg"
              alt="launching"></div>
        </div>
      </div>
      <div class="text-center my-5 hidden md:flex justify-center"><svg width="454px" height="166px"
          viewBox="0 0 454 166" version="1.1" xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.5">
            <g transform="translate(-974.000000, -4888.000000)" fill="#979797" fill-rule="nonzero">
              <path
                d="M1421.30162,5048.07776 L1426.18004,5039.405 L1427.92319,5040.38552 L1421.17319,5052.38552 L1420.30162,5053.93499 L1419.43004,5052.38552 L1412.68004,5040.38552 L1414.42319,5039.405 L1419.30162,5048.07776 L1419.30162,5039.89526 L1419.30162,5038.39776 L1421.30162,5038.39776 L1421.30162,5039.89526 L1421.30162,5048.07776 Z M974,4888 L976,4888 L976,4900 L974,4900 L974,4888 Z M974,4912 L976,4912 L976,4924 L974,4924 L974,4912 Z M974,4936 L976,4936 L976,4942.5515 C976,4944.30448 976.23722,4946.02511 976.700112,4947.68026 L974.774017,4948.21892 C974.262203,4946.38884 974,4944.48701 974,4942.5515 L974,4936 Z M981.562855,4958.69043 L982.843345,4957.15409 C985.782933,4959.60414 989.391444,4961.11985 993.25127,4961.47202 L993.069546,4963.46375 C988.802404,4963.07442 984.811533,4961.3981 981.562855,4958.69043 Z M1005.22282,4963.60589 L1005.23341,4961.60592 L1017.23324,4961.66943 L1017.22266,4963.6694 L1005.22282,4963.60589 Z M1029.22249,4963.73291 L1029.23307,4961.73294 L1041.2329,4961.79644 L1041.22232,4963.79642 L1029.22249,4963.73291 Z M1053.22215,4963.85992 L1053.23274,4961.85995 L1065.23257,4961.92346 L1065.22198,4963.92343 L1053.22215,4963.85992 Z M1077.22182,4963.98694 L1077.2324,4961.98696 L1089.23223,4962.05047 L1089.22165,4964.05044 L1077.22182,4963.98694 Z M1101.22148,4964.11395 L1101.23206,4962.11398 L1113.2319,4962.17748 L1113.22131,4964.17746 L1101.22148,4964.11395 Z M1125.22114,4964.24096 L1125.23173,4962.24099 L1137.23156,4962.3045 L1137.22098,4964.30447 L1125.22114,4964.24096 Z M1149.22081,4964.36798 L1149.23139,4962.368 L1161.23122,4962.43151 L1161.22064,4964.43148 L1149.22081,4964.36798 Z M1173.22047,4964.49499 L1173.23106,4962.49502 L1185.23089,4962.55853 L1185.2203,4964.5585 L1173.22047,4964.49499 Z M1197.22014,4964.622 L1197.23072,4962.62203 L1209.23055,4962.68554 L1209.21997,4964.68551 L1197.22014,4964.622 Z M1221.2198,4964.74902 L1221.23038,4962.74905 L1233.23022,4962.81255 L1233.21963,4964.81252 L1221.2198,4964.74902 Z M1245.21946,4964.87603 L1245.23005,4962.87606 L1257.22988,4962.93957 L1257.2193,4964.93954 L1245.21946,4964.87603 Z M1269.21913,4965.00305 L1269.22971,4963.00307 L1281.22954,4963.06658 L1281.21896,4965.06655 L1269.21913,4965.00305 Z M1293.21879,4965.13006 L1293.22938,4963.13009 L1305.22921,4963.19359 L1305.21862,4965.19357 L1293.21879,4965.13006 Z M1317.21846,4965.25707 L1317.22904,4963.2571 L1329.22887,4963.32061 L1329.21829,4965.32058 L1317.21846,4965.25707 Z M1341.21812,4965.38409 L1341.2287,4963.38411 L1353.22854,4963.44762 L1353.21795,4965.44759 L1341.21812,4965.38409 Z M1365.21778,4965.5111 L1365.22837,4963.51113 L1377.2282,4963.57463 L1377.21761,4965.57461 L1365.21778,4965.5111 Z M1389.21745,4965.63811 L1389.22803,4963.63814 L1400.41276,4963.69733 C1400.69851,4963.69885 1400.98359,4963.70607 1401.26788,4963.71898 L1401.17717,4965.71692 C1400.91957,4965.70522 1400.6612,4965.69868 1400.40217,4965.69731 L1389.21745,4965.63811 Z M1411.78093,4969.55545 L1412.99046,4967.96264 C1416.36727,4970.52688 1418.90641,4974.0594 1420.24165,4978.09261 L1418.34299,4978.72118 C1417.13537,4975.07343 1414.83738,4971.87642 1411.78093,4969.55545 Z M1419.30162,4990.39776 L1421.30162,4990.39776 L1421.30162,5002.39776 L1419.30162,5002.39776 L1419.30162,4990.39776 Z M1419.30162,5014.39776 L1421.30162,5014.39776 L1421.30162,5026.39776 L1419.30162,5026.39776 L1419.30162,5014.39776 Z">
              </path>
            </g>
          </g>
        </svg></div>
      <div class="text-center my-5 md:hidden"><svg width="16px" height="74px" viewBox="0 0 16 74" version="1.1"
          xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" opacity="0.499627976">
            <g transform="translate(-377.000000, -6231.000000)" fill="#979797" fill-rule="nonzero">
              <g transform="translate(122.000000, 679.000000)">
                <g transform="translate(37.000000, 2110.000000)">
                  <path
                    d="M226.009082,3511.7103 L231.960955,3501.30143 L233.697157,3502.2942 L226.86282,3514.24637 L225.980355,3515.78966 L225.119712,3514.23409 L218.454384,3502.18686 L220.204397,3501.21863 L226.009082,3511.7103 Z M225.500025,3441.99296 L227.499975,3442.00704 L227.408428,3455.00672 L225.408478,3454.99264 L225.500025,3441.99296 Z M225.316931,3467.99231 L227.316881,3468.0064 L227.225334,3481.00608 L225.225384,3480.99199 L225.316931,3467.99231 Z M225.133837,3493.99167 L227.133787,3494.00575 L227.079127,3501.76746 L227.04224,3507.00543 L225.04229,3506.99135 L225.079177,3501.75338 L225.133837,3493.99167 Z">
                  </path>
                </g>
              </g>
            </g>
          </g>
        </svg></div>
      <div class="md:flex items-center py-10">
        <div class="md:w-1/2 md:pr-6 lg:pl-12 mb-6 md:mb-0">
          <div class="xl:w-3/4 md:w-full w-2/3 md:ml-auto md:mx-0 mx-auto"><img
              src="../../static/support-&amp;-maintenance.svg" alt="support-&amp;-maintenance"></div>
        </div>
        <div class="w-full md:w-1/2 md:px-6">
          <div class="text-center xl:w-3/4 md:w-full md:w-2/3 md:mr-auto md:mx-0 mx-auto">
            <h1 class="font-heading uppercase tracking-lg md:normal-case md:tracking-sm text-2xl md:text-3xl mb-4">
              Support et Maintenance</h1>
            <p class="text-lg text-grey leading-normal sm:px-0 px-4">Nous ne nous arrêtons pas après le lancement. Nous fournissons des services de maintenance et de sécurité pour que votre application reste active et fonctionne parfaitement!</p>
          </div>
        </div>
      </div>
    </section>
 
    <section class="container my-24">
      <div class="lg:w-2/3 mx-auto mb-10">
        <h1 class="font-heading font-semibold text-5xl text-center tracking-sm mb-4">Notre équipe</h1>
        <p class="text-xl text-grey text-center leading-normal">
          Nous sommes une équipe jeune et ambitieuse de développeurs et de concepteurs travaillant ensemble pour créer des produits vraiment exceptionnels qui aident les entreprises à se connecter avec leurs utilisateurs cibles.
      
        </p>
      </div>
      <div class="flex flex-wrap md:flex-no-wrap md:justify-between justify-center md:py-24 py-12 text-center">
        <div class="md:1/3 w-full mb-12 md:mb-0">
          <div class="w-48 h-48 rounded-full overflow-hidden mx-auto"><img src="https://pbs.twimg.com/profile_images/913909736269058048/FeZCRyEQ_400x400.jpg" alt="Moustapha-cheih" class="w-full">
          </div>
          <div class="lg:w-2/3 md:w-4/5 w-2/3 mx-auto text-center">
            <h3 class="font-heading uppercase my-4 tracking-lg">Moustapha Cheikh</h3>
            <p class="text-base text-grey text-center leading-normal mb-4">Développeur &amp; Data scientist.</p>
          </div>
        </div>

      </div>
    </section>
  


  </Layout>
</template>

<script>
  export default {
    data() {
      return {
        formData: {},
      }
    }, 
    metaInfo: {
      title: 'Accueil'
    }
  }
</script>