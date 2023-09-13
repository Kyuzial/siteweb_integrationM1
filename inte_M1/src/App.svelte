<script>
  // Votre code JavaScript ici
</script>

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<main class="container mx-auto p-4">
  <!-- Grille de la page -->
  <div class="grid grid-cols-1 gap-4">
    <!-- Barre de navigation en haut de la page -->
    <div class="navbar bg-base-300">
      <div class="flex-1">
        <a href="https://www.uvsq.fr/" class="btn btn-ghost normal-case text-xl">
          UVSQ
        </a>
      </div>
      <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
          <li>
            <a href="https://instagram.com/gs.isn?igshid=NjIwNzIyMDk2Mg==">
              Instagram
            </a>
          </li>
          <li><a href="https://discord.gg/hJ5nRewRpX">Discord</a></li>
        </ul>
      </div>
    </div>

    <div>
      <p>
        Bienvenue à tous et à toutes pour cette journée d'intégration.
        Le but de cette journée est que vous appreniez à vous connaître et que vous passiez un bon moment. À la clé de cet événement, certaines équipes auront le droit à des prix. De plus, une collation est offerte ainsi que des pulls à la fin de l'événement.
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
      <div>
        <p>
          Rendez-vous au bâtiment Buffon. Une fois au bâtiment, montez au premier étage et répondez à la question :
        </p>
        <p>Quelle association est sur le campus parmi les réponses suivantes ?</p>
        <!-- Réponses possibles -->
        <button class="btn">InOO1</button>
        <button class="btn">Malibu</button>
        <button class="btn">PCFSchool</button>
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
      <div class="container mx-auto p-4">
        <p>
          Sortez du bâtiment Buffon. Montez la pente et rendez-vous au bâtiment Germain, devant la porte du CROUS/restaurant universitaire. Ensuite, répondez à la question :
        </p>
        <p>Qu'est-ce qu'une graduate school ?</p>
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
      <div class="container mx-auto p-4">
        <p>
          Partez du bâtiment Germain en direction du bâtiment Descartes puis prenez-vous en photo devant Descartes ou avec la vue qu'offre la terrasse de Descartes, puis envoyez la photo au compte Instagram :
        </p>
        <button class="btn">Instagram</button>
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
      <div>
        <p>
          Une fois la photo faite, passez par la forêt pour vous rendre à la bibliothèque universitaire et répondez à la question :
        </p>
        <p>Que signifie ISN ?</p>
      </div>
    </div>

    <!-- Étape 5 : BU -> Stades -->
    <div>
      <p>
        Bravo, vous avez fini la visite de la fac. Maintenant, rendez-vous au stade à côté de la bibliothèque universitaire pour faire quelles épreuves mentales et sportives.
      </p>
    </div>

    <!-- Étape 6 : Épreuves sportives -->
    <div>
      <p>Description des épreuves</p>
    </div>
  </div>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
