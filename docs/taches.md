# Tableau des tâches

> Planifiez vous-même, puis tenez le tableau à jour. Une preuve : un commit, un test vert, un document.

| Tâche | Prévu | Fait le | Preuve |
| --- | --- | --- | --- |
| Poste et dépôt prêts ; besoin compris ; documents commencés | 2026-11-02 | du 02-03 Novembre 2026 | https://github.com/emmanuela-brou/brief-4-journal-meteo/commit/3fc302fa63bddae167902532e771f4c72e856b0e |
| Fiche 2 : lire et écrire le JSON | 2026-11-02 | 2026-11-03 | https://github.com/emmanuela-brou/brief-4-journal-meteo/commit/0c879265088b1601ea56506a248582a5b27d2a3e |
| Fiche 3 : ajouter et lister ; choix 1 et 2 ; erreurs |2026-11-02 |2026-11-04 |https://github.com/emmanuela-brou/brief-4-journal-meteo/commit/e18c4873f74e96bb6081abe75e40a107ad187485 |
| Fiche 4 : rechercher et trier ; choix 3 et 4 |2026-11-03 |2026-11-04 |https://github.com/emmanuela-brou/brief-4-journal-meteo/commit/61066deda052a19d7175941393a95e8685f476d5 |
| Fiche 5 : synthèse ; choix 5 |2026-11-03 |2026-11-04 |https://github.com/emmanuela-brou/brief-4-journal-meteo/commit/1cd5b28f123b9c1a1fb2f56462d42681e833cd27 |
| Tests par un camarade ; mes propres tests | | | |
| Fiche agronomique ; README ; documents |jour 1 2026-11-02 |jour 2 |voir fichier fiche-agronomique.md et README.md|
| Dépôt cloné et lancé ailleurs ; démonstration répétée | | | |
| Bonus | | | |

**Blocages** (le message exact, ce que j'ai essayé, la solution) : 
1- Le message exact : Renvoie une COPIE triée par température croissante, avec un comparateur numérique.
Deux relevés égaux gardent leur ordre d'origine. Le tableau reçu ne doit pas changer d'ordre. Renvoie une COPIE triée par pluie croissante, avec un comparateur numérique.
Deux relevés égaux gardent leur ordre d'origine. Le tableau reçu ne doit pas changer d'ordre.
Dans le fichier recherche.js, je ne savais pas comment faire pour pourvoir classer les température et la pluie de façon croissante.
2- ce que j'ai essayé : avec l'aide de ChatGpt j'ai essayé de comprendre comment cela fonctionne, apres explication et exercice à l'appuie j'ai ecrit un code qui affichais rouge avec vérification.
3- solution : la solution etait de placer les comparateurs  dans le bon sens afin d'obetenir le resultat qui est de classer de façon croissante.
