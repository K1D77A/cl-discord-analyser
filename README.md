# cl-discord-analyser
Download all the images stored in your discord cache from discord servers

Discord has a cache that they keep which contains many different links, this lets you download all the images that are in those links


Either clone the repo and or just copy and paste and load into repl
change into package
(in-package :discord-cache-download)
change the values of \*cache-dir\* and \*save-dir\* to what you want and then run
(request-and-save-all)

Don't adjust the sleep time because we don't really want to spam discord servers. 
