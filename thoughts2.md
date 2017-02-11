So, I changed the file on Authorea and added citations. Now I want to bring in the file to my local repo (git pull?), create a thoughts2.md and append those few lines to the html file.

Now if I went ahead and placed another reference and then modified the thoughts2.html using the cite class equals ltx_cite raw v1 within quote marks, would this work?

Say we cite Leonard's work \\cite{leonard2016} then went ahead and modified this document on thoughts2.html, appended as before and tested. Would it work?

Now a pattern emerges.
When we work with markdown on my own machine and push html to Authorea through git then, for citations, I do not use pandoc's own modifications, rather use two backslashes and add cite command like I would with LaTeX. Then in the resulting html file, I will change the cites to cite class equals ltx_cite raw v1 within quote marks and close the tag.

Wonder if I can ask pandoc not to touch certain tags while conversion? So the next test is to see if I can use pandoc to convert the html from authorea (say I add a bunch of citations and tables, and figures), bring it into my local disk, again work on it and push it back. Use --parse-raw?

So, now I go ahead and make some changes in the authorea page and work from there. 
