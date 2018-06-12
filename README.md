# GitHub-Git-Create-Extension
I found a script on here, on GitHub actually, with similar functionality that I based THIS project on, but it wasn't to my liking.  It was barely working, in that user input could easily bring it to its knees with fatal bugs or cause it to enter erroneous data into the .git/config files, etc.  I've fixed these issues, handled arguments to the script properly...Overall, it's a vast improvement toward what that person had created.  I would link to him for idea credits but I lost the link and no clue whom it was that owned it.

Anywho.

Save this bash script in /usr/local/bin or /usr/bin or anywhere in your $PATH so you can launch without abs. path necessary.  Once it's in your path, git has this neat feature that you can now use the git CLI client itself to use this custom bash script!  Just run `git create <repository name>`  I thought that was super cool.  All works released under WTFPLv2, which is Copyfree, public domain waiver basically, and some may consider it a giant spit in the face to the copyright licenses most are accustomed to, or the forced-libre license such as GPLv3 etc.  I can't support any GPL versions, as they are all considered harmful and are almost akin to a cancer on FOSS.  Once a project gets GPL'd code, it's over with.

Anyways, no more politics.  Hope this helps someone besides me.  I'll have license posted shortly.
