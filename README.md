# Akad Template für die, die es brauchen

## Version 
1.0 (18.04.2025)

## Notizen
Eure Daten könnt ihr oben in template.tex eintragen
Die Eigenständigkeitserklärung stammt direkt von dem neuen (Stand 04.2025) KI Kompass von der AKAD
Inhaltsverzeichnis hat Einzeiligen Abstand
Der Rest 1,5
Zitierstiel ist nach AKAD per Fußnote und AuthorYear (Quellen werden in references.bib abgelegt)

Es gibt zusätzlich einen .vscode Ordner für Visual Studio Code, damit biber ordentlich kompiliert. 
VS Code meckert vermutlich in template.tex wegen Biber rum, das kann man aber ignorieren. Vielleicht handle ich das irgendwann mal.

Sonst müsst ihr folgende Befehle ausführen
pdflatex template.tex
biber template
pdflatex template.tex
pdflatex template.tex

## Für die, die sich auskennen

imports.tex - handelt die Importierungen 
titlemacros.tex - handelt die Titelseite und die Eigenständigkeitserklärung, am Ende wird das Inhaltsverzeichnis, Abbildungsverzeichnis und Tabellenverzeichnis gesetzt
