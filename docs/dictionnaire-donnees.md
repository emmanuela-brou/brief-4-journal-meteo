# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | M08 |
| date | date de relevé | texte | AAA-MM-JJ |2026-11-03|
| temperature(C)|Temperature de l'air | nombre |valeur numerique positive ou négative |°C | 30 |
| pluie(mm) | Quantité de pluie enrégistrée | nombre | >= 0| mm | 15 |
| humiditeAirPct |humidité relative de l'air  |nombre  |comprise entre 0 et 100 | % | 84 |

**Listes de valeurs autorisées** : similaire aux instructions de validation des différents champs.

**Sources** : basé sur le fichier SUJET.md et le fuchier de donnees.
