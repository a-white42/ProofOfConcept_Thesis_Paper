# ProofOfConcept_Thesis_Paper
This is my thesis template paper written in LaTeX as a proof of concept for FOAR705

Purpose:

This template is written using the Overleaf implementation of the LaTeX document preparation system. It was designed and tested using the Overleaf online LaTeX editor (https://www.overleaf.com) but has also been tested in other freely available LaTeX editors such as TexMaker and TexStudio. 


Result:
This is a detailed template for writing a masters thesis paper in philosophy. The template is organized with explanatory notes and command syntax and is broken up into organised chapters under the sub-folder called chapters. e.g. introduction.tex, chapter02.tex, chapter03.tex, chapter04.tex, conclusion.tex or appendix.tex. During the writing process I will only need to edit these chapter files, which wihttps://www.duplicati.com/downloadll consist mainly of plain text. Should I need an additional chapter, for example, chapter 5, I will just need to create a new file (or copy-rename) and old file and then add \chapter{Chapter Five Title} and \input{chapters/chapter05} into the main.tex file. 

Disaster recovery information:

Disaster recovery information is confined to my thesis proper documents and associated files (such as notes, ebooks, papers in pdf format etc.)

All of the files for the Proof Of Concept Thesis template are done in Overleaf and are committed to github (https://github.com/a-white42/ProofOfConcept_Thesis_Paper). This services the purpose of having tracking in terms of version control and for the purposes of backup in case of an unforseen disaster in which Overleaf is hacked or stops working. As an addition backup and offline functionality Overleaf is configured to sync with my Dropbox account both as a secondary backup, but also as a means of working offline in a local LaTeX editor in case of internet outage. The Dropbox sync folder is \Apps\Overleaf\ To work offline, you only need to edit the required document in any LaTeX editor, or any plain text editor (Atom is a good open source text editor, found at https://atom.io/) and when the local Dropbox syncs the Dropbox server the files will automatically sync with Overleaf.   

Dupliciti:

Secondly, I have Duplicati installed, when I used to backup my other work documents, and this is set to back up all the data located in my Dropbox folder to a an external hard drive and a local harddrive. I backup the Dropbox on a local hard drive just in case the contents of Dropbox is compromised. For example, let as same a hacker deletes files on a local Dropbox and it syncs to all Dropbox drives. All local and online files would have been removed. By having both an external hard drive version and a local version means we can plan for either a hacker or a damaged/lost computer.  

In case of disas2.0.4.23-2.0.4.23_beta_20190714.noarch.rpmter: Loss of file, or corruption.
In the worst case of file corruption or a file has gone missing there are several courses of action one could take. 
Both github and Overleaf provides a method of recovering an older files through the version control/history facility.

Overleaf:
1. Select the project in which a file is missing, corrupted, or that you might want to go back to an earlier version. 
2. Select the History tab at the top right of the web interface.
3. Scroll down until you find the correct file. (you can check by clicking on files to see what the content was on a particular date.)
4. Select the "download project at this version"
5. Unzip the file and check the content of the desired file. 
6. From here we can either copy and paste content into the current online version or upload this f2.0.4.23-2.0.4.23_beta_20190714.noarch.rpmile to over-write the current online version.


github:
1. Select file you want
2. Select History
3. You are then presented with a list of every time the file has been committed to github. This emphasises the importance of committing your project regularly. 
4. From here you can search for the older version you might want, or for some text you might want to copy into a newer version. 


Duplicati:

1. Open Duplicati
2. Select restore backup
3. select backup to restore or search

Recovering large quantities of files is beyond the scope of this plan as it involves a lot of time and detail. Duplicati has a disaster recovery page specifically for recovering large numbers of files. 
https://duplicati.readthedocs.io/en/latest/08-disaster-recovery/



Overleaf:
Recovering complete project in Overleaf from github. The Thesis Project can be imported into Overleaf, is a worse case scenario where the overleaf project has been deleted or hacked.  
Procedure:
1. From the https://www.overleaf.com/project page select 'New Project'
2. Choose import from github
3. Select appropriate project (for example, ProofOfConcept_Thesis_Paper)


In case of disaster: New Computer required: 
1. Install Linux Fedora found at https://getfedora.org/
    - boot cd or usb
    - partition hard drive or use VLM
    - reboot system after install (10-15 mins)
2. install Dropbox, instructions finstall.packages(c("tidyverse"))ound at https://www.dropbox.com/install-linux
3. Sync Dropbox (this will restore all data from the Dropbox online server)
4. Update system using $ sudo dnf update
5. Install Firefox (login to enable sync)
6. Download and install Duplicati for Fedora https://www.duplicati.com/download
    - Install mono for fedora. Mono is an opensource implementain of the .NET framwork. 
    - $ sudo dnf install mono-complete
    - $ sudo dnf install [name of duplicati file].rpm
8. install additional software:
    - $ sudo dnf install R
    - $ sudo dnf install texlive
    - $ sudo dnf install texlive-biblatex
    - $ sudo dnf install texmakerinstall.packages(c("tidyverse"))
    - $ sudo dnf install gnome-tweak-tool
9. Login to guthub and get new computer varification code.
