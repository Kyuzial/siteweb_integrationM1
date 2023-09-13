<script>
  // Votre code JavaScript ici
</script>

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<main class="container mx-auto p-4">
  <!-- Grille de la page -->
  <div class="grid grid-cols-1 gap-4">
    <!-- Barre de navigation en haut de la page -->
    <div class="navbar bg-base-300">
      <div class="flex-1">
        <a
          href="https://www.uvsq.fr/"
          class="btn btn-ghost normal-case text-xl"
        >
          UVSQ
        </a>
      </div>
      <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
          <li>
            <a href="https://www.instagram.com/gs.isn/">
              Instagram
            </a>
          </li>
          <li><a href="https://discord.gg/hJ5nRewRpX">Discord</a></li>
        </ul>
      </div>
    </div>

    <div class="rounded-lg p-6 shadow-lg">
      <p class="text-2xl font-bold text-center">
        Bienvenue à tous et à toutes pour cette journée d'intégration.
      </p>
      <p class="mt-4 text-lg">
        Le but de cette journée est que vous appreniez à vous connaître et que vous passiez un bon moment.
      </p>
      <p class="mt-4 text-lg">
        À la clé de cet événement, certaines équipes auront le droit à des prix.
      </p>
      <p class="mt-4 text-lg">
        De plus, une collation est offerte ainsi que des pulls à la fin de l'événement.
      </p>
    </div>
    

    <!-- Étape 1 : Fermat -> Buffon -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-1">
      <!-- Colonne 1 -->
      <div class="p-4 bg-white rounded-lg shadow-md">
        <!-- Plan de l'étape -->
        <img src="src/planfermat--buffon.jpg" alt="Plan de l'étape 1" />
      </div>
      <!-- Colonne 2 -->
      <div class="container mx-auto p-4 flex flex-col items-center">
        <p class="text-2xl font-bold text-center mb-4">
          Rendez-vous au bâtiment Buffon.
        </p>
        <p class="text-lg text-center mb-4">
          Une fois au bâtiment, montez au premier étage et répondez à la question :
        </p>
        <p class="text-lg text-center mb-4">
          Quelle association est sur le campus parmi les réponses suivantes ?
        </p>
        <!-- Réponses possibles -->
        <div class="flex flex-col items-center">
          <button class="btn my-2 px-6 py-2">InOO1</button>
          <button class="btn my-2 px-6 py-2">Malibu</button>
          <button class="btn my-2 px-6 py-2">PCFSchool</button>
        </div>
      </div>
    </div>
    

    <!-- Étape 2 : Buffon -> Germain/CROUS -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-1">
      <!-- Colonne 1 -->
      <div class="p-4 bg-white rounded-lg shadow-md">
        <!-- Plan de l'étape -->
        <img src="src/planbuffon--germain.jpg" alt="Plan de l'étape 2" />
      </div>
      <!-- Colonne 2 -->
      <div class="container mx-auto p-4 flex flex-col items-center">
        <p class="text-2xl font-bold text-center mb-4">
          Rendez-vous au bâtiment Buffon.
        </p>
        <p class="text-lg text-center mb-4">
          Montez la pente et rendez-vous au bâtiment Germain, devant la porte du CROUS/restaurant universitaire. Ensuite, répondez à la question :
        </p>
        <p class="text-lg text-center mb-4">
          Qu'est-ce qu'une graduate school ?
        </p>
      </div>
    </div>

    <!-- Étape 3 : Germain/CROUS -> Descartes -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-1">
      <!-- Colonne 1 -->
      <div class="p-4 bg-white rounded-lg shadow-md">
        <!-- Plan de l'étape -->
        <img src="src/plangermain--descartes.jpg" alt="Plan de l'étape 3" />
      </div>
      <!-- Colonne 2 -->
      <div class="container mx-auto p-4 flex flex-col items-center">
        <p class="text-2xl font-bold text-center mb-4">
          Rendez-vous au bâtiment Descartes.
        </p>
        <p class="text-lg text-center mb-4">
          Partez du bâtiment Germain en direction du bâtiment Descartes puis
          prenez-vous en photo devant Descartes ou avec la vue qu'offre la
          terrasse de Descartes, puis envoyez la photo au compte Instagram :
        </p>
        <a href="https://www.instagram.com/gs.isn/" class="btn mb-4">Instagram</a>
        <p class="text-lg text-center mb-4">
          La meilleure photo remportera un prix
        </p>
      </div>
    </div>

    <!-- Étape 4 : Descartes -> BU -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-1">
      <!-- Colonne 1 -->
      <div class="p-4 bg-white rounded-lg shadow-md">
        <!-- Plan de l'étape -->
        <img src="src/plandescartes-bu.jpg" alt="Plan de l'étape 4" />
      </div>
      <!-- Colonne 2 -->
      <div class="container mx-auto p-4 flex flex-col items-center">
        <p class="text-2xl font-bold text-center mb-4">
          Rendez-vous à la BU.
        </p>
        <p class="text-lg text-center mb-4">
          Une fois la photo faite, passez par la forêt pour vous rendre à la bibliothèque universitaire et répondez à la question :
        </p>
        <p class="text-lg text-center mb-4">
          Que signifie ISN ?
        </p>
        <!-- Réponses possibles -->
        <div class="grid grid-cols-1 gap-2">
          <div class="text-center">
            <button class="btn px-6 py-2">Informatique et Sciences du Numérique</button>
          </div>
          <div class="text-center">
            <button class="btn px-6 py-2">International school of Nantes</button>
          </div>
          <div class="text-center">
            <button class="btn px-6 py-2">Institution des Sciences Numériques</button>
          </div>
        </div>
      </div>
    </div>

    <div class="p-6 rounded-lg shadow-lg">
      <h1 class="text-2xl font-bold mb-4">Étape 5 : De la BU aux Stades</h1>
      <div class="mb-6">
        <p class="text-lg">
          Félicitations ! Vous avez terminé votre visite de la faculté. Il est maintenant temps de vous rendre aux stades, situés à proximité de la bibliothèque universitaire, pour participer à des épreuves mentales et sportives.
        </p>
      </div>
    
      <h2 class="text-xl font-semibold">Étape 6 : Détails des Épreuves</h2>
      <h3 class="text-lg font-medium mt-4">Quelques Règles</h3>
      <div class="mb-4">
        <p class="text-base">
          Chaque équipe doit se concerter et choisir trois jeux parmi les quatre proposés.
        </p>
        <p class="text-base">Chaque épreuve peut rapporter un maximum de 10 points.</p>
      </div>
    
      <div class="border-t-2 mb-4"></div>
    
      <h3 class="text-lg font-medium">Liste des Épreuves</h3>
      <h4 class="text-xl font-semibold mt-4">Épreuve Sportive : Balle au Prisonnier</h4>
      <div class="mb-4">
        <p class="text-base">
          Une équipe affronte une autre équipe tirée au hasard et ne joue qu'un match.
        </p>
        <p class="text-base">L'équipe gagnante obtient entre 5 et 10 points.</p>
        <p class="text-base">L'équipe perdante obtient entre 0 et 5 points.</p>
        <p class="text-base">Le temps pour remporter un match influence le score obtenu.</p>
      </div>
    
      <div class="border-t-2 mb-4"></div>
    
      <h4 class="text-xl font-semibold">Épreuve de Cohésion : Max de Passes</h4>
      <div class="mb-4">
        <p class="text-base">
          Une équipe affronte une autre équipe tirée au hasard et ne joue qu'un match.
        </p>
        <p class="text-base">
          L'objectif est d'effectuer le maximum de passes de balle cumulées au cours d'un match.
        </p>
        <p class="text-base">Il est autorisé d'intercepter la balle en vol.</p>
        <p class="text-base">
          Un match est divisé en deux mi-temps de 2 minutes pour que chaque équipe puisse s'engager.
        </p>
        <p class="text-base">
          Le nombre de points attribués est déterminé une fois tous les matchs joués en fonction du nombre de passes effectuées par chaque équipe.
        </p>
      </div>
    
      <div class="border-t-2 mb-4"></div>
    
      <h4 class="text-xl font-semibold">Épreuve d'Adresse : Chamboule Tout</h4>
      <div class="mb-4">
        <p class="text-base">Dix boîtes disposées en pyramide.</p>
        <p class="text-base">
          Une équipe joue à la fois, chaque membre a deux tirs pour faire tomber sa pyramide.
        </p>
        <p class="text-base">
          Le nombre de points est la moyenne des boîtes tombées pour l'équipe.
        </p>
      </div>
    
      <div class="border-t-2 mb-4"></div>
    
      <h4 class="text-xl font-semibold">Épreuve de Communication : Time's Up</h4>
      <div class="mb-4">
        <p class="text-base">Une équipe affronte une autre équipe en deux manches de 45 secondes chacune.</p>
        <p class="text-base">
          Durant chaque manche, un membre de l'équipe doit faire deviner à son coéquipier un maximum de mots.
        </p>
        <p class="text-base">Chaque joueur doit jouer au moins une fois chaque rôle.</p>
        <p class="text-base">
          Le nombre de points est attribué une fois tous les matchs joués en fonction du nombre de mots devinés.
        </p>
        <p class="text-base">Manche 1 : Description du mot à deviner.</p>
        <p class="text-base">Manche 2 : Le joueur ne peut dire qu'un seul mot pour faire deviner.</p>
      </div>
    </div>
  </div>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
