# Journal météorologique de la ferme

> Projet individuel du SAS DFS, brief 4 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

Le journal météorologique de la ferme est utilisé par le responsable pédagogique de la ferme, il permet de saisir les données, les stocker dans un fichier JSON, de retrouver une journée en fonction de sa date de saisir ou de son identifiant et de lister une courte série de 10 jours. Il faut savoir qu'on ne peut pas parler de changement de climat car le climat se caractérise sur une période de 30 ans et il ne faut pas confondre l'humidité du sol à l'humidité de l'air, on décrit uniquement la météo passée de ses journées.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-4-journal-meteo.git
cd brief-4-journal-meteo
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

 *Cochez seulement ce qui marche : `- [x]`.*

- [x] Données lues et enregistrées dans `donnees/releves.json`
- [x] Ajouter un relevé, saisies invalides refusées sans arrêter le programme
- [x] Lister les relevés, message si le journal est vide
- [x] Rechercher par identifiant ou par date ; journées pluvieuses (au moins 10 mm)
- [x] Trier par température ou par pluie
- [x] Synthèse : température moyenne, minimale et maximale de la série, cumul de pluie, journées pluvieuses
- [ ] Bonus : supprimer et modifier un relevé (choix 6 et 7)
- [ ] Bonus : tri par température décroissante, journée la plus chaude

## Données

|Champ| |Contenu| |Unité|
|id| |Identifiant unique, par exemple M08| |-|
|date| |Date du relevé, au format AAAA-MM-JJ| |-|
|temperatureC| |Température de l'air : un nombre, négatif ou décimal possible
| |°C|
|pluieMm| |un nombre positif ou nul| |mm|
|humiditeAirPct| |Humidité relative de l'air : un nombre entre 0 et 100| |%|

## Limites

 On distingue quelques limites :
- IL est impossible d'en deduire quels type de climat est observé sur la region, car on ne peut se baser sur une courte series de dix jours de relevés, il en faut environ 30 ans pour tirer une conclusion sur le type de climat.
- On ne peut prédire ni inondation, ni sécheresse, ni stress hydrique en raison du seuil de 10 mm. 
- L'humidité relative de l'air n'est pas l'humidité du sol : connaître l'une ne permet pas de connaître l'autre.
Le journal ne vérifie pas que les dates se suivent, sans doublon ni trou : seule la validité de chaque date est contrôlée.
- On ne peut pas également connaître le minimum et le maximum de chaque journée car une seule température est prise par jour.

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

Brou Grâce-Emmanuela KOUAME, emmanuela-brou. Entraide : Junior DJONGON, KAMAGATE Salia Abdala, . Ils m'ont aidé a travailler sur mon fichier app.js, dans l'explication et le fonctionnement.
