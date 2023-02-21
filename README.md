
# Updating Geonewsletter

1. Move Articles.csv to minio 
2. Copy Articles.csv to server
3. Archive previous index-en.html and index-fr.html files
4. In script, update:
  * line 10 to set the language (either "en" or "fr") 
  * line 11 to set issue date (e.g. "22-Nov")
5. Knit document
6. Rename index.html to index-en.html or index-fr.html
7. Repeat steps 4-6 for other language
8. Open html files to edit and:
  * Find replace "xE9" with "é"
  * change tab <title> from index.utf8 to:
      * en: Geonewsletter!
      * fr: Bulletin d'information géo !
9. Copy index files to minio and add a version to GC docs
10. Share for review/test for bugs 
      
