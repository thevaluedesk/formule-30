# 🏎️ FORMULE 30 · À consommer de préférence avant 2056

Jeu de course arcade créé par Louis pour les 30 ans de Matthias (30 août 2026).
Une capsule temporelle jouable : 6 circuits qui rejouent 20 ans d'amitié, des fiches pilotes façon Apple,
et des prédictions scellées jusqu'au 30 août 2056, jour de ses 60 ans.

Classé PEGI 30. Peut contenir des moules et de la techno.
Une amitié, ça se bonifie comme un bon vin. Rendez-vous en 2056.

## Jouer

Ouvrir `index.html` dans n'importe quel navigateur. C'est tout : 1 seul fichier, aucune dépendance,
aucun serveur, ça marche même hors ligne. La musique techno est générée par le code (aucun MP3).

- **Ordinateur** : flèches ← → pour piloter, ↑ pour accélérer, ↓ pour freiner, Échap pour la pause.
- **iPhone / mobile** : toucher la moitié gauche ou droite de l'écran pour tourner, l'accélération est automatique. En paysage c'est encore mieux.
- Sortir de la piste fait perdre de la vitesse. Le chrono enregistre le record de chaque circuit.
- Battre l'A1 de Louis, c'est pour l'honneur. Les casquettes Callaway et, à Dubaï, les costumes de chez Chital se ramassent au passage.

## Les 6 circuits

1. **Collège de Marcq** : la rencontre en 5ᵉ.
2. **Marina de Dubaï** : les 2 ans de V.I.E, détour chez Chital compris.
3. **Golfe de Cargèse** : tous les étés en Corse.
4. **Le Marathon** : 42,195 km dans les jambes.
5. **La Route de la Moule** : l'export international, sous la pluie du Nord.
6. **GP des 30 Ans** : la course de nuit finale.

Chaque victoire débloque une carte souvenir sur le mur.

## La Capsule 2056

La capsule est verrouillée (🔒) tant que les 6 circuits du championnat ne sont pas gagnés : il faut la mériter.
Le code `MOULE` tapé au clavier la déverrouille en secours.

Le soir de l'anniversaire, ouvrir « Capsule 2056 » et lancer le mode soirée : chacun répond aux 11 questions.
Le bouton « Sceller » verrouille les réponses jusqu'au **30 août 2056** (impossible de les lire avant, le jeu refuse).

Les réponses sont d'abord stockées dans le navigateur du téléphone utilisé. Pour les graver définitivement dans le jeu :
1. Après le scellage, la page affiche un **code** (bouton « Copier le code »).
2. Coller ce code dans `index.html`, variable `CONFIG.capsuleScellee` (entre les guillemets).
3. Commit + push. Les prédictions font alors partie du site pour les 30 prochaines années.

## Publier sur GitHub Pages (gratuit, permanent)

1. Créer un dépôt public sur GitHub (par exemple `formule-30`).
2. Pousser ce dossier dessus.
3. Sur GitHub : Settings → Pages → Source : `Deploy from a branch` → branche `main`, dossier `/ (root)` → Save.
4. Le jeu est en ligne à `https://<pseudo>.github.io/formule-30/` au bout de 2 minutes.

Conseil longévité : garder aussi une copie de `index.html` ailleurs (iCloud, clé USB, AirDrop aux 2).
Le fichier s'ouvrira toujours dans 30 ans, avec ou sans GitHub.

## Personnaliser

Tout est dans le bloc `CONFIG` en haut du `<script>` de `index.html`. Les lignes marquées ✏️ :

- `dateFete` : la date exacte de l'anniversaire.
- `souvenirs` : les textes des 6 cartes souvenirs (mettre les vraies anecdotes, les private jokes).
- `compare` : les lignes du comparateur de pilotes.
- `capsuleScellee` : le code des prédictions scellées (voir plus haut).

## Secrets

- Taper `MOULE` au clavier dans les menus : tout se déverrouille (utile en 2056 pour revoir les cartes sans rejouer, quoique).
- Ouvrir `index.html#debug` : circuits raccourcis, tous niveaux ouverts (pour tester).
- Il y a une lettre cachée dans le code source. Elle attendra 2056.
