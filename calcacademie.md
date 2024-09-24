<!--

title: "Calcacadémie : maîtriser les fonctions de base et quelques fonctions avancées du tableur libre Calc"  

author: Xavier Chard-Hutchinson, Damien Belvèze

date: février 2021

email: damien.belveze@univ-rennes.fr 

language: fr 

comment: ce support a été édité et publié pour la première fois par Xavier Chard-Hutchinson et Damien Belvèze sur le site https://focus.univ-rennes1.fr et proposé aux collègues de la Bibliothèque Universitaire de Rennes 1 en février 2021

-->


# Calcacadémie

![LibreOffice 7.5 Calc, Wikimedia Commons, CC:by-sa](logo.png)

Découvrir les potentialités du tableur libre Calc ou affermir ses bases et élargir ses compétences.



## Evaluer son niveau

Cet atelier a pour but de vous aider à progresser dans l'apprentissage de CALC.

Les activités sont réparties par niveau et proposent une liste d'exercices à effectuer à partir des fichiers fournis.

Si vous savez déjà faire un tableau croisé dynamique mais que vous souhaitez vous entraîner à la réalisation de graphiques, vous pouvez attaquer le niveau intermédiaire.

Si vous savez déjà faire un tableau croisé dynamique et que vous maîtrisez les diagrammes, vous pouvez avancer au Niveau Avancé.

Sinon, vous pouvez commencer au niveau le moins avancé.

## Niveau débutant

### Consignes générales

Consigne générale : les exercices doivent être faits avec le logiciel libre Calc

Télécharger le [support de l'exercice](classeur1.csv)

### tâches et Objectifs


| **Partie** | **Objectif** | **fonction** | **niveau de difficulté**|
| --- | --- | --- | --- |  
| 1.1 | Ouvrir le fichier: formater les séparations et le type des colonnes, attention ici PPN = texte (pour ne pas perdre les 0 qui font partie du PPN). | Import CSV | ⭐  |
| 1.2 | Largeur de colonne : redimensionner B, C et D à 5 cm de largeur.<br><br>Supprimer la colonne N « date création ». | Formater son tableau | ⭐  |
| 1.3 | sélectionner les non-manquants colonne L. | Filtrer des données | ⭐  |
| 1.4 | Copier la sélection dans une nouvelle feuille. Nommer la feuille « exemplaires présents » | Gérer les feuilles de données | ⭐  |
| 1.5 | Dans la nouvelle feuille « exemplaires présents », masquer les colonnes K,L,M.<br><br>Insérer deux nouvelles colonnes après N. | Formater son tableau | ⭐  |
| 1.6 | Texte en colonne sur N « Dernier prêt »avec séparateur : tiret<br><br>Renommer les colonnes :<br><br>Dernier prêt Année / Dernier prêt Mois / Dernier prêt Jour | Texte en colonne | ⭐⭐ |
| 1.7 | On veut travailler par cote. Déplacer la colonne Cotes de H en U. Texte en colonnes : largeur fixe : entre cote et sous-cote ( faire attention à la largeur de la prévisualisation). Faire le ménage : supprimer la colonne vide au milieu du tableau et renommer les colonnes : cote / sous-cotes. | Texte en colonne | ⭐⭐ |
| 1.8 | Appeler l’auto-filtre pour enregistrer les en-têtes . Trier dans l’ordre croissant dans cet ordre des colonnes T puis U | Tri des données | ⭐  |
| 1.9 | Tableau croisé dynamique pour obtenir le nombre de prêts par titre identifié par son n° PPN (du Sudoc) puis par son n° notice Koha sur la période, en calculant la somme des prêts sur la période | Table dynamique | ⭐⭐⭐ |
| 1.10 | Modifier le tableau croisé généré pour faire apparaître pour chaque ligne, son titre, son auteur, son éditeur et son année d’édition. | Table dynamique | ⭐⭐ |
| 1.11 | On veut l’année du dernier prêt le plus récent.<br><br>Dans la feuille « exemplaires présents », il faut d'abord que la colonne M soit formatée comme nombre (pour faire l'objet d'un tri dans le tableau dynamique). On voit qu'il faut effacer le formatage de la colonne, bloquée en texte (représenté par l'apostrophe devant une donnée) : faire texte en colonne avec séparateur : vide. Les années s’affichent à droite de la colonne : elles ont été reconnues comme nombres. | Changer le format des données | ⭐  |
| 1.12 | On revient sur le tableau dynamique pour afficher l’année du dernier prêt le plus récent.<br><br>Copier le tableau dynamique dans une nouvelle feuille nommée "sélection", puis dans cette nouvelle feuille, effacer la première ligne pour que les en-têtes soient en ligne 1.<br><br>Dans la feuille"sélection", filtrer sur plusieurs colonnes les titres qui ont été prêtés moins de deux fois et qui soit ont été prêtés pour la dernière fois au plus tard en 2017, soit qui ont paru il y a plus de cinq ans (avant 2015). Copier le résultat dans une nouvelle feuille qu’on renomme « Candidats désherbages ». | Table dynamique/Filtrer | ⭐⭐ |
| 1.13 | Dans la nouvelle feuille « Candidats désherbages », ajouter une colonne I « Date moyenne de parution ». En I2, appeler une fonction pour faire la moyenne des dates de parution. | Fonctions | ⭐⭐ |
| 1.14 | Ajouter une colonne J intitulée "décision", on veut créer un menu de choix déroulant : sélectionner la première case, Validation :à partir d’une liste (« en rayon, magasin, pilon »). | Validation des données | ⭐⭐ |
| 1.15 | Puis ajouter une colonne K « Lien Sudoc », pour créer un lien vers la notice dans le Sudoc. Copier en L1 le texte suivant : « https://www.sudoc.fr/ ». Appeler une fonction qui va créer le texte du lien : d’abord en cellule L2, créer un texte qui associe le texte en L1 suivi du contenu de A2, qui nous donne le PPN. En cellule M2, appeler une fonction qui va rechercher sur le web l’adresse en L2.<br><br>Question subsidiaire : Comment faire en une seule étape ? | Fonction concaténer | ⭐⭐⭐ |
| 1.16 | Remplir automatiquement le reste des lignes de la colonne L à partir de L2, vérifier que la liste s’affiche partout. Puis de la colonne M à partir de M2. Vérifier que les liens fonctionnent. | Remplissage automatique | ⭐  |
| 1.17 | Il nous manque l’ISBN. Comment le récupérer à ce niveau sans tout refaire ?<br><br>En colonne O, cellule O2 appeler la fonction RechercheV, en recherchant le n° de Notice B2 dans la feuille « exemplaires présents » et y aller chercher l’ISBN.<br><br>Remplir automatiquement les lignes suivantes. | Recherche verticale | ⭐⭐⭐⭐ |


## Niveau intermédiaire

### Consignes générales

Consigne générale : les exercices doivent être faits avec le logiciel libre Calc
Télécharger le [support de l'exercice](classeur2.ods)

### Consignes, Objectifs

Insérer sous le tableau des données les diagrammes suivants, en faisant figurer leur titre 

| Type de diagramme | Titre | Données | Période |
| --- | --- | --- | --- |
| 2.1 Colonnes empilées | évolution de l'utilisation des collections | nombre des prêts | De 2014 à 2019 |
| 2.2 Lignes seules | évolution de l'utilité des collections | taux de rotations | De 2012 à 2019 |
| 2.3 Secteur éclaté | répartition des acquisitions | dépenses | En 2019 |

2.4 Le dernier diagramme doit afficher les valeurs sur chaque secteur dans des étiquettes.

2.5 Chaque diagramme doit faire figurer sa légende et suivre le code couleur suivant :

| **Intitulé COLLECTIONS** | **Couleur** |
| --- | --- |
| MEDECINE | Bleu Clair 2 |
| ODONTOLOGIE | Brique Clair 2 |
| SCIENCES FONDAMENTALES | Citron Vert Clair 2 |
| PHARMACIE | Or Clair 2 |
| CULTURES DE LA SANTÉ | Mauve Clair 2 |

## Niveau avancé

### Consignes générales

Télécharger le [support de l'exercice](classeur3.csv)
Les noms ont en grande partie été arbitrairement générés par Randat](https://randat.com/)

Consigne générale : les exercices doivent être faits avec le logiciel libre Calc

### Consignes, Objectifs


| **partie** |**Consigne** | **Objectif** | **Difficulté** |
| --- | --- | --- | --- |
| 3.1 | Trier les cellules de la colonne G par ordre alphabétique croissant en englobant dans le tri les colonnes H et I | Tri | ⭐  |
| 3.2 | Compter le nombre d'occurrences du prénom violet dans la base des étudiants, afficher le chiffre en B111 | Ctr+F / fonction NB.SI | ⭐ / ⭐⭐⭐ |
| 3.3 | changer la casse de la colonne A et B (tout en minuscule) | formatage du texte | ⭐⭐ |
| 3.4 | Rechercher remplacer par des voyelles sans accent tous les caractères diacritiques dans les colonnes A et B (é, è, ë, ô, etc.) | formatage du texte | ⭐⭐ |
| 3.5 | Séparer le texte présent dans la colonne E en deux parties : avant le @ en colonne E, @ et nom de domaine du mail en colonne E | texte en colonnes | ⭐⭐ |
| 3.6 | Dans la colonne J, afficher automatique la valeur Admis ou Recalé (si le score est supérieur ou égal à 50 : admis, s'il est inférieur à 50 : recalé) | formatage conditionnel | ⭐⭐⭐ |
| 3.7 | Dans un tableau, afficher la somme des admis et celle des recalés dans le groupe 3 | tableau croisé dynamique | ⭐⭐⭐ |
| 3.8 | Créer une nouvelle colonne C vide, s'en servir pour inverser les valeurs présentes dans les colonnes A et B (mettre le prénom en A et le nom en B), laisser la colonne C vide | copier-coller de colonnes | ⭐  |
| 3.9 | Dans une nouvelle colonne, afficher la liste des étudiants présents dans la base des étudiants mais qui n'ont pas réalisé l'activité (afficher le résultat en colonne Y (Nom) et Z (Prénom) | tri avec extraction sans doublons) | ⭐⭐⭐⭐ |
| 3.10 | Dans une nouvelle colonne, afficher la liste des étudiants absents dans la base des étudiants mais qui ont bien réalisé l'activité | tri avec extraction sans doublons | ⭐⭐⭐⭐ |
| 3.11 | Dans la colonne C, concaténer les valeurs présentes en colonne A et B (prénom + nom en réservant un espace entre les deux) | concaténation | ⭐⭐⭐ |
| 3.12 | Dans les colonnes AA et AB afficher automatiquement les mails et le numéro de groupe des personnes dont les noms et les prénoms se trouvent en Y et Z (au besoin prévoir de concaténer prénoms et noms présents en colonne Y et Z comme on l'a fait pour plus haut) | Recherche verticale | ⭐⭐⭐⭐ |