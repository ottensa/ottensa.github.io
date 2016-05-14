# ottensa.github.io
## Vorgehensweise
1) Metadaten schreiben
'''
---
layout: post						// Typ, immer 'Post'
title: Besuch aus Deutschland		// Titel, der angezeigt wird
thumbnail: /img/thailand-2.jpg		// Das Bildchen, das auf der Übersicht angezeigt wird
location: Phnom Penh, Kambodscha	// Der Ort, wo ich den Artikel verfasst habe
excerpt: 							// optionaler Auszug, der auf der Übersicht angezeigt wird
social: /social/thailand-2.jpg		// Bild, das bei Facebook angezeigt wird
---
'''

2) Artikel in Markdown verfassen

3) Bilder
	a) Sortieren
	b) Umbenennen
	c) Schrumpfen: sips --resampleHeight 1536 *.jpg
	d) Upload zu Flickr
	e) Alben auf Flickr anlegen: "YYYY-MM - Name"

4) Flickr Alben in den Artikel einbinden
{% include gallery.html album="ALBUMID" %}

5) Korrektur lesen

6) Upload
'''
git add .
git add *
git commit -m "Nachricht"
git push origin master
'''

7) Facebook überprüfen
https://developers.facebook.com/tools/debug/og/object/

8) Veröffentlichen