
textproc
=============================

This folder contains:

textproc_document_paths_ecrm_101001.xml
-----------------------------

useful for: wisski_textproc, wisski_editor
requires: wisski_pathbuilder

It contains the pathbuilder paths "Refers to" and "Topic" and a group
"Document", that contains both paths. These can be used as templates for
modelling annotated texts and their two basic relations:
reference (annotated entities) and topic (the instance the text is displayed
with).
After importing the file, make sure to configure the textproc module to use the
paths. Goto Administer -> Site configuration -> Wisski module settings ->
Textproc -> Document settings and set the dropdown boxes to the paths and
groups accordingly.

NOTE: The file uses classes and properties of the Erlangen CRM version 101001.
If you use another version of the Erlangen CRM, change the URIs in the file
accordingly before import.



