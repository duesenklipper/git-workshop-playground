# git workshop playground

Dieses Repository enthält ein paar Branches und Commits, mit denen wir im
Workshop spielen können.

Die Dateien enthalten nichts sinnvolles, einfach nur Text.

carl-eric.menzel @ codecentric.de


Folgendes Skript hilft den Fehler zu finden:

   #!/bin/bash

   if ! grep -qi error *.java
   then
     exit 0
   else
     exit 1
   fi

