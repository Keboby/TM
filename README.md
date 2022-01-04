# TM
Ci-joint se trouvent les fichiers correspondant aux différentes parties de mon TM: le programme de création des données, le programe dédié à l'entraînement du modèle, et enfin le programme lié au modèle d'inférence.

J'ai rajouté dans le répositoire 4 extraits audio de mon programme sur la chanson 'So Far Away' de Dire Straits.
Tous les extraits sont tirés d'une version MIDI de ladite chanson, disponible gratuitement sur internet.
(cf. 'So far away from me midi', _FreeMidi.org_, https://freemidi.org/download3-13090-so-far-away-from-me-dire-straits)

Il y a d'abord un extrait des instruments seuls, représentant ce que reçoit le programme en input (NB: il n'y a que les guitares, basses et pianos) – cet extrait est nommé 'test-song-no-drums.mp3'.
Ensuite, on trouve le rythme de batterie généré, accompagné des autres instruments. J'en ai fait deux versions: une première avec le rythme complet ('test-song-with-generated-drums.mp3'), et une deuxième version ('test-song-with-quantized-drums.mp3') avec le même rythme mais sans les informations de vélocité ou de micro-timing (=>juste les notes). Cette dernière sert à illustrer le fait que, sans ces informations supplémentaires, un rythme sonne moins "humain", même si ses notes ne sont pas mauvaises – un bon rythme sans "groove" perd son côté humain et réaliste, et redevient robotique.
Finalement, j'ai rajouté un extrait avec uniquement le rythme généré ('only-generated-drums.mp3'), pour mieux apprécier les légères variations de vélocité et de micro-timing, infimes mais toujours perceptibles.


En outre, j'ai désormais codé un petit site internet en python pour que tout le monde puisse utiliser librement mon algorithme. Il suffit d'y déposer un fichier MIDI sans batterie pour ensuite obtenir un nouveau fichier MIDI avec la batterie générée automatiquement. J'encourage toute personne à essayer le site et à me donner du feedback sur ce dernier et la qualité du produit fini.
L'adresse du site est: http://RobertoGoelzerTM.pythonanywhere.com/

Je mets aussi désormais à disposition mon travail de maturité, aussi bien ici que sur mon site internet.


Bonne lecture,
Roberto Goelzer
