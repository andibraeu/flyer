# Freifunk-Flyer zur Auslage in Schulen

Es gibt noch immer Schüler:innen ohne Internetanschluss zu Hause. Das ist schlecht. Freifunk könnte helfen. Vor dem beidseitigen Drucken ggf. die 2. Seite drehen, etwa durch Entfernen der Option *notumble*.

## Requirement for Ubuntu

sudo apt install texlive texlive-latex-base texlive-luatex texlive-latex-extra texlive-fonts-extra texlive-lang-german -y

## Mit Latex übersetzen

lualatex -interaction=nonstopmode flyer.tex
