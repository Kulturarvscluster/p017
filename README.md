# P017 R project
This R project is part of the P017 DEICproject LUDVIG.
For now we share files on Google Drive: 
https://drive.google.com/drive/folders/1509yN43uFM0qSaLNK1nKavn-82zbO6Kj?usp=sharing

The project answers questions formulated in this document:
https://docs.google.com/document/d/1YeikoaHe36B4ajvxBHqMdovM7XVoSFLXBb1biJjotLs/edit?usp=sharing

The R project is located here:
https://drive.google.com/drive/folders/1gF9tvrjsVSZ6wNqNlm4sLtxVMY7R8Ol0?usp=sharing

* The R notebooks are in the notebooks directory here: 
https://drive.google.com/drive/folders/1jZKqyNtfp0gvKJohvPYOs1_3_yLV41xM?usp=sharing
* The xslt scripts are in the script directory here:
https://drive.google.com/drive/folders/1Yo_uLDUxmkel1xNLvE255ykPtfYjt4cg?usp=sharing
* The data is in the data directory here:
https://drive.google.com/drive/folders/1vCb1XDo4WT-GUc1ygYtOppdfTuMcSNUf?usp=sharing
  * The input files (TEI) are in the input directory here:
  https://drive.google.com/drive/folders/1vCb1XDo4WT-GUc1ygYtOppdfTuMcSNUf?usp=sharing
  * The JSON files are in the jsonl directory here:
  https://drive.google.com/drive/folders/1vCb1XDo4WT-GUc1ygYtOppdfTuMcSNUf?usp=sharing
  * The output files (CSV) are in the output directory here:
  https://drive.google.com/drive/folders/1r8bHmAwEPLEA4dgsHhb1z6HLJe-dUfqs?usp=sharing

## Read a Play
The "read_a_Play.rmd" notebook explains how to transform a play from TEI to JSONL and how to read it.

## Find Characters
The "find_speakers.rmd" notebook finds characters; both speakers and characters in <stage> tags and in speach. 
**_Work in progress._**

The notebook writes a number of output files. For each play, these files will be produced:
* play_all_speakers.csv: navne på alle karakterer med replikker.
* play_speakers_by_scene.csv: alle karakterer med replikker opdelt på akt og scene.
* play_stage_instructions_by_scene.csv: regibemærkninger <stage> opdelt på akt og scene.
* play_combined_stage_instructions.csv: alle regibemærkninger.
* play_speaker_stage_instructions_by_scene.csv: regibemærkninger <speaker-stage> opdelt på akt og scene.

## Dramatiske Overgange
The "dramatiske_overgange.rmd" notebook finds the first and last spoken words in each scene. The output is written to:
* play_first_sentence.csv: første sætning i hver scene.
* play_last_sentence.csv: sidste sætning i hver scene.

