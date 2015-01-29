# TJLDH procédure

1. Mettre à jour le fichier .md qui va bien
2. générer le HTML correspondant via bouton 
3. dans page web correspondante: effacer tout entre `<body >` et paragraphe final (footer.js)
4. coller
5 lancer remplacer partout prédéfini:

	<p>(<img src="../../images/tjldh/[0-9]+.jpg" alt="[^"]*") title="([^"]*)" (id="[^"]*")( class="[^"]*")? /></p>

par

	<p><figure\4>\1 title="\2" \3 />\n<figcaption>\2</figcaption>\n</figure>



# Tables (liens et images)

Récupérer le HTML généré via Chrome/inspecter

# EPUB

Faire une validation xml des fichiers .htm (xhtml)
Référencer les fichiers dans content.opf
Mettre à jour la feuille de style
remplacer dans index.htm les liste.htm par liens.htm et illustrations.htm

