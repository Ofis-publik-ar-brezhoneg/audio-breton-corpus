# Corpus audio breton
Corpus audio de phrases en breton, créé par l'IRISA et l'Office public de la langue bretonne dans le cadre du projet de synthèse vocale du breton.

## Description du corpus
### Voix Aziliz et Per

Aziliz et Per sont des voix féminine et masculine enregistrées entre 2021 et 2022. Elles disposent de près de 20 heures d'enregistrements à partir de textes de sources variées.

#### Données Aziliz
| Dossier | Nombre de fichiers | Durée |
| ------- | ------------------ | -------- |
| A1      | 7928 | 10:15:01 |
|A201-dialog_documents|632|01:08:03|
|A201-dialog_mozilla|1777|01:35:14|
|A203-tales|556|00:54:18|
|A204-poems|529|00:35:13|
|A205-recipes|131|00:12:25|
|A207-proper_names|1319|00:38:26|
|A208-letters_numbers|56|00:01:43|
|A212-text_documents|456|00:40:08|
|A212-text_mozilla|1435|01:10:41|
|**Total**|**14819**|**17:11:12**|

#### Données Per
| Dossier | Nombre de fichiers | Durée | Commentaires |
| ------- | ------------------ | -------- | -- |
|P1-part1-slowed_tempo|7182|08:50:05|Cette session correspond principalement à du contenu journalistique, adminitratif et technique. Une réduction du tempo de 10% a été appliquée.|
|P1-part2-original_tempo|746|00:52:03||
|P201-dialog_documents|634|01:12:18||
|P201-dialog_mozilla|1777|01:26:45||
|P203-tales|556|00:55:55||
|P204-poems|529|00:41:18||
|P205-recipes|131|00:08:49||
|P207-proper_names|1875|00:47:45|Per a été enregistré deux fois en lisant des noms de ville à voix haute, mais avec des intonations différentes|
|P208-letters_numbers|54|00:01:25||
|P212-text_documents|452|00:27:10||
|P212-text_mozilla|1435|01:04:41||
|**Total**|**15371**|**16:28:14**||





## Fichiers de données `.tsv`

À chaque dossier contenant des fichier `.wav` pour un locuteur ou une locutrice correspond un fichier `.tsv` dans le dossier `sentences`, avec les entêtes suivantes :

- champ 0 : nom du fichier `.wav` associé
- champ 1 : transcription normalisée
- champ 2 : transcription textuelle
- champ 3 : transcription phonétique
- champ 4 : `1` si le fichier audio a déjà été créé, `0` si le fichier audio était prévu mais n'a pas été créé (les autres champs ne doivent pas être pris en compte, ou sont vides)
- champ 5 : `1` si la normalisation a été validée, `0` si la normalisation n'a PAS été validée (les champs normalization et phonetization ne doivent pas être pris en compte, ou ils sont vides).
- champ 6 : `1` si une transcription phonétique manuelle est disponible, `0` sinon
- champ 7 : texte source
- champ 8 : aide à l'enregistrement (optionnel)
- champ 9 : nombre de couches pour le *diphone covering* (seulement pour les voix plus récentes "loeiz" et "rozenn")

## Nommage des fichers audio

A correspond à aziliz  
P correspond à per  



