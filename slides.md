---
title: Référentiel des Applications du Système d'Information
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
.custom-default-12px {
  font-size: 12px;
}
.custom-background-12px {
  background-color: #050505;
  color: #ffffff;
  font-size: 12px;
}
</style>


<h1 style="text-align: center;">Référentiel des Applications</h1>

<br>

<br>

<br>

## [Cartographie du SI](./2)

<br>


<br>

## [Doctrine](./9)

<div class="abs-br m-6 flex gap-2">
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

<h2 style="text-align: center;">Contexte</h2>

<br>

&#x1F6A7; *introduire les éléments codir2* 

<br>

- Le référentiel contient l'ensemble des applications et services(*produits numériques*) utilisés au sein du système d'information;
  
- Il permet de centraliser, structurer, et gérer efficacement pour un accès et une utilisation optimisés;

- Il "participe à la protection, à la défense et à la résilience du système d’information"[(*)](https://cyber.gouv.fr/publications/cartographie-du-systeme-dinformation). 

- Il est adressé à l'ensemble des acteurs du Système d'information.

<!--
- &#x2705; De nombreux référentiels contenant des informations sur les applications et services;
  
- &#x2705; L'unicité des noms et descriptions d'applications ne sont pas effectives entre les référentiels. 

- &#x2705; Aucun identifiant unique et partagé entre les référentiels;

- &#x2705; Connaissances toutes relatives des impacts sur le système d'informations.  

-->

<br>

<!--
<h3 style="text-align: center;">Tous concernés</h3>
-->

<div class="abs-br m-6 flex gap-2">
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
  
- **Facilité d'accès** : Avoir une vue précise et d'ensemble des produits (*fiche du produit*);
  
<v-clicks>    

  <span v-mark.box.red="1"> &#x2705; patrimoine applicatif du ministère; </span>
 
  <span v-mark.box.red="2"> &#x2705; l'ensemble des applications hébergées et supervisées </span>

- **Gestion des dépendances** : Comprendre les interconnexions et dépendances entre applications;

- **Amélioration de la maintenance** : Simplifier les processus de mise à jour et d’audit;

- **Amélioration de l'exploitabilité** : Mesurer plus facilement les impacts d'incidents opérationnels;G

</v-clicks>

<div class="abs-br m-6 flex gap-2">
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

- **Application centrale** : Il s'agit du <span v-mark.box.red="2">point de vérité</span>, (*coeur de la fleur*) partageant les <span v-mark.box.red="3">données utiles et communes</span> (*numéro d'affaire, identifiant unique, nom, description, etc.*) à l'ensemble des contributeurs et usagers du SI;

- **Modules associés** : Applications et outils externes (les *<span v-mark.box.red="4">pétales</span>*) connectés au référentiel. La relation coeur et pétales est réalisée via l'identifiant unique qui est un UUID; 

   
- **Gestion des interfaces et des flux de données** : Représentation des inter-actions applicatives et leurs flux de données.

- **Suivi des flux** : Outils de monitoring pour détecter et résoudre les problèmes potentiels.

<!-- pétales points d'acquisition et de consommation -->

</v-click>


<div class="abs-br m-6 flex gap-2">
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

- &#x1F511; **Identification des applications** : Chaque consommateur de l'API est identifié de manière unique afin d'accéder aux données; 

- &#x1F504; **Mise à jour Automatique** : Les informations du référentiel sont maintenues à jour sans intervention manuelle augmentant la qualité des données tout <span v-mark.box.red="3">  en réduisant la charge de travail de l'agent. </span>


</v-click>


<div class="abs-br m-6 flex gap-2">
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
  
- **Conformité et sécurité** : Facilitation des audits, amélioration de la sécurité et meilleur appréciation des actes de compromission;
  
- **Temps à valeur ajoutée** : Redonner du temps utile aux agents et partenaires du ministère.

<!-- https://cyber.gouv.fr/faq-systemes-dinformation-dimportance-vitale -->

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: two-cols
transition: fade-out
class: 'custom-default-12px'
---

# Architecture

- Chaque consommateur(*pétales*) du service est authentifié (***OAuth2***);
- **Les consommateurs/fournisseurs(producteurs)** en cible (*mais pas que*) sont :
  - le processus traitant des demandes clients (ex: intialisation du *numéro d'affaire*): producteur/consommateur;
  - les services financiers: *consommateur*;
  - les consoles cloud (applications) : *consommateur/producteur*;
  - les solutions de ticketing (ex: *minitil*...) : *consommateur*, le service de pilotage d'hébergement : *consommateur*; 
  - les services archi infra / réseaux : *producteur/consommateur*, les services d'infrastructure (ex: opencds, cmdbs) : *producteur/consommateur*;
  - les services de supervision: *consommateur*;
  - la mission de dette IT: *consommateur*;
  - Passage IAP (applications): *consommateur*;
  - les sous direction ayant des besoins spécifiques et opérationnels (ex: *via grist*) : *consommateur* à terme producteur;
  - ...
 
::right::

```mermaid
%%{
  init: {
    'theme': 'default',
    'themeVariables': {
      'primaryColor': '#BB2528',
      'primaryTextColor': '#fff',
      'primaryBorderColor': '#7C0000',
      'lineColor': '#F8B229',
      'secondaryColor': '#006100',
      'tertiaryColor': '#fff',
      'fontSize': 14px
    }
  }
}%%
architecture-beta

    group api(cloud)[API]

    service gateway(internet)[Gateway] in api
    service db(database)[Postgresql] in api
    service disk1(disk)[Storage] in api
    service backend(server)[NestJs] in api
    service authent(server)[OAuth2] in api
    junction junctionCenter in api
    junction junctionRight in api
    
    gateway:B -- T:authent
    gateway:T -- B:backend
    db:L -- R:backend
    disk1:T -- B:db

    group frontend(cloud)[frontend]

     service front(server)[VueJS_Dsfr] in frontend 
     front:R --> L:gateway

    group tableur(cloud)[petales]

     service grist(server)[grist] in tableur 
     grist:R <--> L:gateway

    group consoledso(cloud)[petales]

     service console(server)[console_dso] in consoledso 
     console:T <--> B:gateway

    group cmdb_cloud(cloud)[petales]

      service cmdb(server)[cmdb] in cmdb_cloud

      cmdb:T <--> B:gateway
    
    junction junctionCenter
```

- **Données essentielles** :
  - **identifiant unique (UUID)**, nom et description de l'application ou services;
  - acteurs (moa, moe, presta), populations ayant accès à l'application (implique le type de SSO);
  - site d'hébergement, niveau de service (dima, pdma), date et durée d'homologation, niveau rgaa etc.

<div class="abs-br m-6 flex gap-2">
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

- Un référentiel des applications bien structuré est essentiel pour un système d'information efficace, sécurisé et évolutif (*aide à la décision et maitrise des risques*)

- Un référentiel des applications accessible et connecté redonnant du temps utiles aux agents.

 
<div class="abs-br m-6 flex gap-2">
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

- Direction Générale et Décideurs Stratégiques;
- Les Métiers;
- Direction de la Transformation Numérique;
- SGAMI;
- Architectes (*d'Entreprise*, *Solution*, *infra*,...);
- SSI;
- Auditeurs et Conformité (*RGPD, RGAA, etc.*);
- Équipes Produits;
- Responsables Exploitations et Supervisions Techniques

<!-- Utilisateurs finaux dans le cas notamment des logiciels utiisés sur le poste de travail -->
<br>


<div class="abs-br m-6 flex gap-2">
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

<br>

### Pour quoi ?

<br>

- **Compréhension globale** : Fournir une vue d'ensemble claire des applications et de leurs interactions pour aider à la prise de décisions stratégiques;
   
- **Sécurité et conformité** : Cartographier les flux de données pour assurer leur sécurité et répondre aux exigences réglementaires;

- **Exploitabilité et impacts opérationnels** : Faciliter la compréhension et la gestion des incidents impliquants des applications;

- **Gestion des changements** : Faciliter l'évaluation des impacts des changements et transformation au sein du système d'informations;

- **Optimisation des ressources** : Identifier les redondances et les opportunités de rationalisation des applications.


  
<div class="abs-br m-6 flex gap-2">
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
<h3 style="text-align: center;font-style: italic;"> #gouvernance </h3>

<br>

- **Mise en place d’un comité de gouvernance** : Le comité regroupe l'ensemble entités et acteurs (*authentifiés*) contribuant à la mise à jour du référentiel. Il permettra par décisions collégiales d'intégrer de nouveaux attributs de données éligibles aux points de vérité (*le coeur*). Superviser l’utilisation des outils d’automatisation, vérifier la conformité et l’alignement avec la stratégie de l’entreprise;
    
- **Journalisation et auditabilité** : Assurer une journalisation complète des actions automatisées pour pouvoir effectuer des audits et retracer les modifications;
   
- **KPIs d'automatisation** : Développer des indicateurs pour mesurer l'efficacité des processus automatisés, comme le taux de mises à jour automatisées ou la réduction du temps de mise à jour.

  
<div class="abs-br m-6 flex gap-2">
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
<h3 style="text-align: center;font-style: italic;"> #interface / intégration </h3>

<br>

<v-click>

- &#x1F500; **Automatisation des collectes initiales** : Mettre en place des traitements, des services pour récupérer et injecter automatiquement les données des applications et des systèmes dans le référentiel ( <span v-mark.box.red="2"> &#x1F6B0; données : MAJO, CANEL v1, PAI, Tableur SDAN  etc... </span> )
- &#x1F50E; **Surveillance des changements** : Déployer des mécanismes qui détectent et présentent automatiquement les changements dans les systèmes tiers (ex: environnements, composants logiciels); 
- &#x2705; **Validation automatisée** : Valider automatiquement des données avant leur intégration dans le référentiel pour assurer la qualité des informations;
- &#x1F440; **Validation manuelle (*stewardship*)** : Ajouter si nécessaire une re-validation manuelle des données pour assurer la qualité des informations (par exemple : dédoublonnage); 
- &#x1F440; **Curation**: Assurer l'amélioration de la qualité des données dans une démarche collaborative.
</v-click>

<div class="abs-br m-6 flex gap-2">
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
    
- **Sensibilisation des utilisateurs** : Informer les utilisateurs sur les avantages de l'automatisation pour encourager leur adoption et leur participation. Une participation qui est au service du collectif.

<div class="abs-br m-6 flex gap-2">
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

La cartographie du Système d'Informations (SI) devient une solution <span v-mark.underline.red="2">proactive</span>, capable de :

- Se mettre à jour en *temps réel*; 
- Répondre rapidement aux changements dans l'écosystème des applications et des technologies;
- <span v-mark.box.red="3">Améliorer à la fois la précision et la fiabilité du référentiel</span>;
- <span v-mark.box.red="4">Permettre une meilleure réactivité face aux évolutions du SI;</span>
- <span v-mark.box.red="5">Permettre également une meilleure maîtrise des risques liés à la transformaton du SI.</span>

</v-click>

<div class="abs-br m-6 flex gap-2">
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
  <a href="https://github.com/dnum-mi/referentiel-applications" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>



