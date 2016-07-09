---
layout: post
title: Assignment 3-File Conversion Script
---

 This blog post is actually the third assignment for the INLS course I am taking this summer (for the future, any other posts titled with "Assignment #-" is also for the course). Currently, we are learning about writing simple scripts and having them run successfully.  For this particular assignment we wrote a script that uses Pandoc. Pandoc is an open-source software that converts files from one format (i.e. from a Word .docx) to another (i.e. a markdown .md file). As that indicates, this script is able to convert documents into different types, specifically into .docx, .odt, .html, and .pdf files. For consistency as a class and ease of troubleshooting, we all started out with a markdown (.md) file that will be converted. 
 
 A secondary parameter to this assignment is the actual markdown file that we each are using.  This file is required to be an original document; a paper, memo, story, etc. that the student wrote theirselves.  I chose to use a short paper on Gisli's Saga that I wrote for a class on the Viking Age (one of the ebst courses I have ever taken). Gisli's saga is about a viking named Gisli who makes blood oaths with his brother and two brother-in-laws to be friendly towards each other, but ofcourse it all falls to [Hel](https://en.wikipedia.org/wiki/Hel_(location)) (pun intended; Gisli's Saga is all in Midgard). But not everything is clear about if the man Gisli went to exact blood vengence upon was the correct man --I think Gisli did right and that is the premise of my paper. 
 
Onwards to the actualy script writing, etc: Pandoc is called to do its magic by the command "pandoc" and switches (think of them as callable parameters that you have to define). Since the source file type is not always going to be the same file type, using the output file switch (-o), followed by a variable (i.e. $INPUTFILE), and lastly the variable with the new file type (i.e. $INPUTFILE.txt) is an easy way to tell Pandoc here is an input file of X type, convert it into a .txt type file. This line can then be repeated and edited to indicate a different output file type in different lines. One thing to know though, is that in order for Pandoc to convert files in the PDF format, TeXLive must also be installed. TeXLive (pronounced tech-live) is a free software package that has the bare basics needed for Pandoc to convert files in the PDF format --without it, Pandoc cannot make PDFs. 

Below are my origin/source file and the converted output files (linked from my GitHub):

[Origin File](https://github.com/inls161/assignment-3-convert-some-documents-NimBreitenfeld/blob/master/GislisSaga.md)

[PDF version](https://github.com/inls161/assignment-3-convert-some-documents-NimBreitenfeld/blob/master/GislisSaga.md.pdf)

[HTML version](https://github.com/inls161/assignment-3-convert-some-documents-NimBreitenfeld/blob/master/GislisSaga.md.html)

[ODT version](https://github.com/inls161/assignment-3-convert-some-documents-NimBreitenfeld/blob/master/GislisSaga.md.odt)

[DOCX version](https://github.com/inls161/assignment-3-convert-some-documents-NimBreitenfeld/blob/master/GislisSaga.md.docx)
