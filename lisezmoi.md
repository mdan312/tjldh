# TJLDH proc�dure

1. Mettre � jour le fichier .md qui va bien
2. g�n�rer le HTML correspondant via bouton 
3. dans page web correspondante: effacer tout entre `<body >` et paragraphe final (footer.js)
4. coller
5 lancer remplacer partout pr�d�fini:

	<p>(<img src="../../images/tjldh/[0-9]+.jpg" alt="[^"]*") title="([^"]*)" (id="[^"]*")( class="[^"]*")? /></p>

par

	<p><figure\4>\1 title="\2" \3 />\n<figcaption>\2</figcaption>\n</figure>



# Tables (liens et images)

R�cup�rer le HTML g�n�r� via Chrome/inspecter

# EPUB

Faire une validation xml des fichiers .htm (xhtml)
R�f�rencer les fichiers dans content.opf
Mettre � jour la feuille de style
remplacer dans index.htm les liste.htm par liens.htm et illustrations.htm

