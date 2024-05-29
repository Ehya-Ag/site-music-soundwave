Description des Pages
1. index.html

La page d'accueil présente SoundWave et met en avant la possibilité de diffuser plus de 20 000 chansons. Elle comprend un en-tête avec des liens de navigation, une zone de contenu principal avec des images promotionnelles et du texte, et un bouton d'appel à l'action pour s'inscrire.
2. signup.html

La page d'inscription permet aux utilisateurs de créer un compte en saisissant leur nom, leur email et leur mot de passe. Elle inclut un formulaire dans une section qui encourage à rejoindre SoundWave.
3. features.html

La page des fonctionnalités présente les différentes options disponibles pour les utilisateurs, telles que la découverte de nouvelle musique, l'accès aux classements, aux albums, etc. Elle comporte des sections avec des images et des descriptions de ces fonctionnalités.
Composants Communs
En-tête

L'en-tête est cohérent sur toutes les pages et contient :

    Un logo avec un lien vers la page d'accueil.
    Des liens de navigation vers les pages des fonctionnalités et d'inscription.

Pied de page (uniquement sur signup.html)

Le pied de page inclut des liens vers les comptes de réseaux sociaux de SoundWave (Twitter et Facebook) représentés par des icônes.
Défis de Style et de Positionnement
Alignement de l'En-tête et du Pied de page

    Défi : Assurer que l'en-tête soit alignée de manière cohérente sur toutes les pages tout en maintenant les liens de navigation correctement positionnés.
    Solution : Utilisation d'une classe CSS commune (head) pour la liste de navigation et application de flexbox pour maintenir une mise en page uniforme.

Positionnement des Images et du Texte

    Défi : Positionner correctement les images et les éléments textuels superposés dans la section promotionnelle de la page d'accueil.
    Solution : Utilisation des positionnements absolu et relatif au sein d'un conteneur parent avec position: relative. Ajustement des propriétés top, left, right, et bottom pour obtenir la mise en page souhaitée.

Conception Réactive

    Défi : S'assurer que la mise en page soit réactive et adaptée à différentes tailles d'écran.
    Solution : Mise en œuvre de media queries dans le CSS pour ajuster les tailles de police, les dimensions des images et les propriétés de mise en page en fonction de la largeur de l'écran.

Alignement du Formulaire sur la Page d'Inscription

    Défi : Aligner proprement les éléments du formulaire (étiquettes et champs de saisie) sur la page d'inscription.
    Solution : Utilisation d'une combinaison de flexbox et d'ajustements de marges pour s'assurer que les champs du formulaire soient uniformément espacés et alignés.