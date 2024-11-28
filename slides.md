---
title: Référentiel des Produits Numérique du Système d'Information
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
download: true
mdc: true
drawings: 
  enabled: true
colorSchema: auto
class: custom-background-14px
---

<style>
.custom-background-14px {
  background-color: #050505;
  color: #ffffff;
  font-size: 14px;
}
.custom-background-12px {
  background-color: #050505;
  color: #ffffff;
  font-size: 12px;
}
</style>


<h1 style="text-align: center;">Référentiel des Produits Numériques</h1>

<br>

<br>

<br>

## [Cartographie du SI](./2)

<br>


<br>

## [Doctrine](./8)

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
  <SlidesTotal />
</div>
---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;">Introduction</h2>

<br>

- Le référentiel des applications représente l'ensemble des produits numériques et logiciels utilisés au sein du système d'information;
  
- Il permet de centraliser, structurer, et gérer efficacement  pour un accès et une utilisation optimisés;

- Il "participe à la protection, à la défense et à la résilience du système d’information"[(*)](https://cyber.gouv.fr/publications/cartographie-du-systeme-dinformation). 

- Il est adressé à l'ensemble des acteurs du Système d'information.

<br>

<h3 style="text-align: center;">Tous concernés</h3>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;">Objectifs du référentiel</h2>

 <br>

- **Centralisation** : Rassembler toutes les fiches produits dans un seul point de vérité;
  
- **Facilité d'accès** : Avoir une vue précise et d'ensemble des produits;
  
<v-click>    

  <span v-mark.box.red="2"> &#x2705; patrimoine applicatif du ministère; </span>
 
  <span v-mark.box.red="3"> &#x2705; l'ensemble des applications hébergées et supervisées </span>

</v-click>

<v-click>

- **Gestion des dépendances** : Comprendre les interconnexions et dépendances entre applications;

- **Amélioration de la maintenance** : Simplifier les processus de mise à jour et d’audit;

- **Amélioration de l'exploitabilité** : Mesurer plus facilement les impacts d'incidents opérationnels;

</v-click>




<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;">Structure du référentiel</h2>

<br>

<v-click>

- **Application centrale** : Il s'agit du <span v-mark.box.red="2">point de vérité</span>, (coeur de la marguerite) partageant les <span v-mark.box.red="3">données utiles</span> (numéro d'affaire, identifiant unique, nom, description, etc.) à l'ensemble des contributeurs et usagers du SI;

- **Modules associés** : Applications et outils externes (les <span v-mark.box.red="4">pétales</span>) connectés au référentiel;
   
- **Gestion des interfaces et des flux de données** : Représentation des inter-actions applicatives et leurs flux de données.

- **Suivi des flux** : Outils de monitoring pour détecter et résoudre les problèmes potentiels.

</v-click>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editeur" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!-- Visualisation des connexions stratégiques entre applications -->

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;">Modules associés</h2>
<h3 style="text-align: center;">automatisation</h3>

<br>

<v-click>

- &#x1F50C; **API Exposée** : Le référentiel expose une API pour permettre <span v-mark.box.red="2"> l’automatisation des mises à jour </span> et l'intégration avec d'autres systèmes;

- &#x1F511; **Identification des applications** : Chaque consommateur de l'API est identifié de manière unique par une **API Key** afin d'accéder aux données; 

- &#x1F504; **Mise à jour Automatique** : Les informations du référentiel sont maintenues à jour sans intervention manuelle augmentant la qualité des données tout <span v-mark.box.red="3">  en réduisant la charge de travail de l'agent. </span>


</v-click>


<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://api-referentiel-applications.apps.app1.numerique-interieur.com/api/v1" target="_blank" alt="API" title="Swagger"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-api-1 />
  </a>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---


<h2 style="text-align: center;">Avantages d'un référentiel centralisé et connecté</h2>

<br>

- **Efficacité opérationnelle** : Réduction des redondances et optimisation des ressources;
  
- **Prise de décision** : Accès rapide aux informations clés pour un meilleur pilotage;
  
- **Conformité et sécurité** : Facilitation des audits et amélioration de la sécurité;
  
- **Temps à valeur ajoutée** : Redonner du temps utile aux agents et partenaires du ministère.

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>
---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;">Conclusion</h2>

<br>

<br>

<br>

- Un référentiel des applications bien structuré est essentiel pour un système d'information efficace, sécurisé et évolutif.

- Un référentiel des applications accessible et connecté redonnant du temps aux agents
  
<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-12px'
---

<h2 style="text-align: center;"> Doctrine </h2>

<br>

### Pour qui ?

<br>

- Direction Générale et Décideurs Stratégiques
- Direction de la Transformation Numérique
- Les Métiers
- Utilisateurs Finaux
- Architectes d'Entreprise et SI
- SSI
- Auditeurs et Conformité (*RGPD, RGAA, etc.*)
- Équipes Produits
- Responsables Exploitations et Supervisions Techniques

<!-- Utilisateurs finaux dans le cas notamment des logiciels utiisés sur le poste de travail-->
<br>


<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;"> Doctrine </h2>

<br>

### Pour quoi ?

<br>

- **Compréhension globale** : Fournir une vue d'ensemble claire des applications et de leurs interactions pour aider à la prise de décisions stratégiques;
  
- **Optimisation des ressources** : Identifier les redondances et les opportunités de rationalisation des applications;
  
- **Sécurité et conformité** : Cartographier les flux de données pour assurer leur sécurité et répondre aux exigences réglementaires;
  
- **Gestion des changements** : Faciliter l'évaluation des impacts des changements et transformation au sein du système d'informations;

- **Exploitabilité** : Faciliter l'exploitation des applications.


  
<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;"> Doctrine </h2>
<h3 style="text-align: center;font-style: italic;"> #gouvernance </h3>

<br>

- **Mise en place d’un comité de gouvernance** : Superviser l’utilisation des outils d’automatisation, vérifier la conformité et l’alignement avec la stratégie de l’entreprise;
    
- **Journalisation et auditabilité** : Assurer une journalisation complète des actions automatisées pour pouvoir effectuer des audits et retracer les modifications;
   
- **KPIs d'automatisation** : Développer des indicateurs pour mesurer l'efficacité des processus automatisés, comme le taux de mises à jour automatisées ou la réduction du temps de mise à jour.

  
<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-12px'
---

<h2 style="text-align: center;"> Doctrine </h2>
<h3 style="text-align: center;font-style: italic;"> #automisation </h3>

<v-click>

- &#x1F500; **Automatisation des collectes initiales** : Mettre en place des traitements, services pour récupérer et injecter automatiquement les données des applications et des systèmes dans le référentiel ( <span v-mark.box.red="2"> &#x1F6B0; données : MAJO, CANEL, PAI  etc... </span> )

- &#x1F50E; **Surveillance des changements** : Déployer des mécanismes qui détectent et présentent automatiquement les changements dans les systèmes tiers (par exemple, modification d'une API ou d'une architecture);
  
- &#x2705; **Validation automatisée** : Ajouter une validation automatique des données avant leur intégration dans le référentiel pour assurer la qualité des informations;
  
- &#x1F440; **Validation de type data stewardship** : Ajouter une validation manuelle des données avant leur intégration dans le référentiel pour assurer la qualité des informations (par exemple : dédoublonnage);
  
- &#x1F440; **Curation**: Assurer l'amélioration de la qualité des données dans une démarche collaborative.
</v-click>

<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;"> Doctrine </h2>
<h3 style="text-align: center;font-style: italic;"> #formations </h3>

<br>

- **Formation des équipes techniques** : Assurer que les équipes en charge de la cartographie, ainsi que les autres contributeurs clés, soient formées aux technologies et aux processus d'automatisation.
    
- **Sensibilisation des utilisateurs** : Informer les utilisateurs sur les avantages de l'automatisation pour encourager leur adoption et leur participation.

<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;"> Doctrine </h2>
<h3 style="text-align: center;font-style: italic;"> #conclusion </h3>

<br>

<v-click>

La doctrine de la cartographie du Système d'Informations (SI) devient une entité <span v-mark.underline.red="2">proactive</span>, capable de :

- Se mettre à jour en *temps réel*; 
- Répondre rapidement aux changements dans l'écosystème des applications et des technologies;
- <span v-mark.box.red="3">Améliorer à la fois la précision et la fiabilité du Référentiel des Produits Numériques</span>;
- <span v-mark.box.red="4">Permettre une meilleure réactivité face aux évolutions du SI;</span>
- <span v-mark.box.red="5">Permettre également une meilleure maîtrise des risques liés à la transformaton du SI.</span>

</v-click>

<div class="abs-br m-6 flex gap-2">
   <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Ouvri dans GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: image-left
image: /images/DALL·E-2024-11-01-13.06.13.jpg
transition: fade-out
class: 'custom-background-14px'
---

<h2 style="text-align: center;">Questions ?</h2>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Editer" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

