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

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [ ] Données lues et enregistrées dans `donnees/releves.json`
- [ ] Ajouter un relevé, saisies invalides refusées sans arrêter le programme
- [ ] Lister les relevés, message si le journal est vide
- [ ] Rechercher par identifiant ou par date ; journées pluvieuses (au moins 10 mm)
- [ ] Trier par température ou par pluie
- [ ] Synthèse : température moyenne, minimale et maximale de la série, cumul de pluie, journées pluvieuses
- [ ] Bonus : supprimer et modifier un relevé (choix 6 et 7)
- [ ] Bonus : tri par température décroissante, journée la plus chaude

## Données

✏️ *Le fichier, le nombre de relevés, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), les unités. Rappelez qu'ils sont fictifs.*

## Limites

✏️ *Au moins trois. Par exemple : dix jours de relevés forment une courte série, ils ne décrivent pas le climat de la région.*

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

✏️ *Prénom NOM, compte GitHub. Entraide : avec qui, sur quoi.*
