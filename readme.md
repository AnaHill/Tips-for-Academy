Here, I will tell my trips&trick for the academy. 
- use version control
- MATLAB
-  COMSOL
- ...

# Use version control ... with your own style
Version control tools, like git, are great for many things.
However, it is not the best for writing documents that are not in pure text format. And, to be honest, learning .git is not so easy for people that are not having astrong technical background or willingess to learn it. 

I do believe that the basics of git is not that difficult that anyone with enough motivation and time can learn it. However, I know that there are many people that are not interested in that learning process. In case of you are one of those that is not interested in to learn e.g. LaTeX nor git, I suggest here a simple but relative effective way to keep track of most important changes during your writing process

In this example, Word-document `my_own_document.docx` located in folder `main\` is used. Document could also be in any other file tape. Sidenote: as discussed, if you are writing markdown or .tex or .txt or in any other pure text file format, you should then really learn to use real version control tools like .git to keep track of changes.

Basically, idea is that 
1) you keep **writing to same document**, no renaming. No document name like my_own_document_draft.docx that will later be renamed to my_own_document_first_submission.docx etc. You might ask why: Shortly, link to that document keeps same (assuming you are sharing it through OneDrive/Googledrive or any other cloud services). And, version history is kept. Keep reading to find out other reasons.
2) when you want to take a backup, you _copy_ that document to backup folder, e.g. `main\backup` (not even necessary, could be located in main folder but this way that folder is kept cleaner)
3) rename copied file to something meaning full but short, e.g. `main\backup\my_own_document_ver2.docx`
   - it is also possible to use a bit more descriptive name, e.g. `main\backup\my_own_document_ver2_before_sending_to_my_supervisor.docx`. However, this is not necessary or even recommended, see the next step.
4) Create list for you safecopies: it can be in .txt or markdown or excel or whatever format you prefer, e.g. `main\backup\safecopylist.xslx`. Here, you list
   - safecopy name, e.g. `my_own_document_ver2.docx`
   - and short description about the changes you made to the document, e.g. _This version was send to my supervisor for his first review_.
5) Keep writing to the original document; when safecopy-snapshot is needed, go back to step 2 and create a new copy of the document.

During writing process, you have
- `main\my_own_document.docx` where you write your text, **all the time**
-  `main\backup\safecopylist.xslx` that describes safecopy-snapshots
-  `main\backup\my_own_document_ver1.docx` safecopy-snapshot number 1
-  `main\backup\my_own_document_ver2.docx` safecopy-snapshot number 2
-  ...

# MATLAB

# COMSOL
## How to empty simulation file without opening it


# Acknowledgment
I warmly thank all my previous colleagues during my academic career.
