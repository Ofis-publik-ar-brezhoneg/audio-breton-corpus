# Audio korpus in breton
Audio corpus of Breton sentences, created by IRISA and the OPAB (Ofis Publik Ar Brezhoneg) as part of the Breton speech synthesis project.

## Description of the corpus
### Aziliz and Per's voices

Aziliz and Per are female and male voices recorded between 2021 and 2022. They comprise nearly 20 hours of recordings based on texts from various sources.

#### Aziliz Data
| File | Number of files | Duration |
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

#### Per Data
| File | Number of files | Duration | Comments |
| ------- | ------------------ | -------- | -- |
|P1-part1-slowed_tempo|7182|08:50:05|This session primarily consists of journalistic, administrative, and technical content. A 10% reduction in tempo has been applied.|
|P1-part2-original_tempo|746|00:52:03||
|P201-dialog_documents|634|01:12:18||
|P201-dialog_mozilla|1777|01:26:45||
|P203-tales|556|00:55:55||
|P204-poems|529|00:41:18||
|P205-recipes|131|00:08:49||
|P207-proper_names|1875|00:47:45|Per was recorded twice reading city names aloud, but with different intonations.|
|P208-letters_numbers|54|00:01:25||
|P212-text_documents|452|00:27:10||
|P212-text_mozilla|1435|01:04:41||
|**Total**|**15371**|**16:28:14**||



## `.tsv` Data Files

Each folder containing `.wav` files for a speaker has a corresponding `.tsv` file in the `sentences` folder, with the following headers:

- Field 0: Name of the associated `.wav` file
- Field 1: Normalized transcription
- Field 2: Text transcription
- Field 3: Phonetic transcription
- Field 4: `1` if the audio file has already been created, `0` if the audio file was planned but was not created (the other fields should not be considered, or are empty)
- Field 5: `1` if normalization has been validated, `0` if normalization has NOT been validated (the normalization and phonetization fields should not be considered, or are empty). - Field 6: `1` if a manual phonetic transcription is available, `0` otherwise
- Field 7: Source text
- Field 8: Recording help (optional)
- Field 9: Number of layers for the *diphone covering* (only for the more recent voices "loeiz" and "rozenn")

## Audio file naming

A corresponds to Aziliz
P corresponds to Per



