# les-voisins-d-abord

# Etapes de la conception du site
1) reflexion sur le thème avant de ce lancer.
 - Que vivons-nous au quotidien ? De quoi avons-nous besoin ? Après refexion, le thème portera sur une association à but non lucratif qui met en relation les voisins entres eux dans ce monde connecté. Le nom de l'association et du site sera "les voisins d'abord".
 - L'objectif est de faire connaitre ses talents à ses voisins proches ou éloignés et d'en faire profiter gratuitement. C'est du donant donant, aujourd'hui quelqu'un à besoin de moi, demain j'aurais sans doute besoin de quelqu'un !
 - Autre objectif important : montrer que vivre dans un monde connecté n'est pas mal en soit, la preuve c'est grace à ce site que des voisins s'entraident.
 
2) Puisque le thème est choisi, je décide de faire un petit wireframe à la main sur feuille A4 (vue mobile en 1er et puis vue desktop). C'était pas demandé dans l'énoncé mais avec cela je vois mieux où je vais.

3) Par contre, je ne me lance pas dans un mokup complet (figma ou adobeXD) car pas encore au point la dessus et l'énnoncé ne le demande pas.

4) Je commence maintenant à coder:
    - Plutôt que de créer un dossier sur mon bureau, d'y faire un 'git init' et d'ajouter un readme.md, je décide de créer un repo sur GitHub avec pour nom "les-voisins-d-abord" en cochant 'ajouter un readme.md'. Je copie ensuite le lien de mon repo. De retour sur mon bureau, je fais un 'git clone". Je rempli ensuite le readme avec les quelques lignes que vous lisez jusque là.
    - En fait c'est plus maintenant que je commence à coder... J'ouvre VSCode, je fait glisser mon dossier fraichement cloné. Je crée ma structure initial de fichiers: index.html, style.css, srcipt.js et un dossier 'medias' qui contiendra les images du site.
    - Je fais un 'git add' et mon 1er commit avec cette structure de fichier. 
    - Je crée et switch sur la branche 'features' (git checkout -b features) qui servira à l'élaboration de mes composants successif du site. A présent je vais uniquement travailler sur cette dernière et quand mes évolutions seront stables je ferais un 'git merge' sur la branche 'main'.
    - 1ère étape: construction html de la home-page. J'inclus Bootstrap via le CDN car cela suffit pour les besoins de l'exercice. J'inclus aussi le lien js de Bootstrap.