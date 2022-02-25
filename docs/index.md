## Word to markdown guide Windows Edition

## Contents
[How to Install PandDoc](#how-to-install-Pandoc)

[Converting a file](#converting-a-file)

[Converting a file from markdown to word doc](#converting-a-file-from-markdown-to-word-doc)

[Be on the lookout for](#be-on-the-lookout-for)

## How to Install Pandoc
1.	Go to the website https://pandoc.org/installing.html
2.	Install the appropriate fill for your system – If you have windows install windows version

## Converting a file
Using PandDoc to convert a word doc into markdown file is fairly easy and straightforward
1.	Open up the terminal and type in this command 
    a.	pandoc MyWordDoc.docx -f docx -t markdown -o MyWordDoc.md
        i.	instead of using MyWordDoc.docx use the name of the file you are trying to convert.
    b. using the command Pandoc -t gfm --extract-media . -o [file].md [file].docx ensures that the pictures are safely stored and show up in the markdown file.
2.	The file now is converted to markdown

## Converting a file from markdown to word doc
1.	Converting form markdown to word is really simple you only need to know the file path and code
2.	Open up terminal and type pandoc “path\document.md” -f markdown -o “path\output.docx”
3.	Be careful when finding the file path as a slight mistake will not allow it to be converted.
 
## Be on the lookout for
    Make sure the the word docs and or markdown docs are in the correct .formats. 
    as word should be in .docx format and markdown in .md
    Ensure that when you take the file path that you are copying it correctly
