# ProofOfConcept_Thesis_Paper
This is my thesis template paper written in LaTeX as a proof of concept for FOAR705

Purpose:

This template is written using the Overleaf implementation of the LaTeX document preparation system. It was designed and tested using the Overleaf online LaTeX editor (https://www.overleaf.com) but has also been tested in other freely available LaTeX editors such as TexMaker and TexStudio. 


Result:
This is a detailed template for writing a masters thesis paper in philosophy. The template is organized with explanatory notes and command syntax and is broken up into organised chapters under the sub-folder called chapters. e.g. introduction.tex, chapter02.tex, chapter03.tex, chapter04.tex, conclusion.tex or appendix.tex. During the writing process I will only need to edit these chapter files, which wihttps://www.duplicati.com/downloadll consist mainly of plain text. Should I need an additional chapter, for example, chapter 5, I will just need to create a new file (or copy-rename) and old file and then add \chapter{Chapter Five Title} and \input{chapters/chapter05} into the main.tex file. 

Disaster recovery:

Disaster recovery is confined to my thesis documents and associated files (such as notes, ebooks, papers in pdf format etc.)

All of the files for the Proof Of Concept Thesis template are committed to github (https://github.com/a-white42/ProofOfConcept_Thesis_Paper) for the purposes of backup in case of disaster. Overleaf is also configured to sync with my Dropbox account both as a secondary backup, but also as a means of working offline in a local LaTeX editor. The Dropbox sync folder is \Apps\Overleaf

Dupliciti:

Secondly, Duplicati is installed and backs up all the data located in my Dropbox folder to any external hard drive. This is   

In case of disaster: Loss of file, or corruption.
In the worst case of file corruption or a file has gone missing there are several courses of action one could take. 
1. both github and Overleaf provides a method of recovering an older file through version control/history.
2. File can be recovered through Duplicati.

Overleaf:
Recovering complete project in Overleaf from github. The Thesis Project can be imported into Overleaf, is a worse case scenario where the overleaf project has been deleted or hacked.  
Procedure:
1. From the https://www.overleaf.com/project page select 'New Project'
2. Choose import from github
3. Select appropriate project (for example, ProofOfConcept_Thesis_Paper)


In case of disaster: New Computer required: 
1. Install Linux Fedora found at https://getfedora.org/
2. install Dropbox, instructions found at https://www.dropbox.com/install-linux
3. Download and install Duplicati for Fedora https://www.duplicati.com/download