#CodePath

### App Description
`TODO://` Add app description
Cette application Android est un petit projet d’apprentissage en Kotlin. Elle propose trois fonctionnalités simples :

Changer la couleur du texte : à chaque clic sur le bouton, la couleur du texte passe en boucle parmi une liste de couleurs prédéfinies.

Changer la couleur du fond : le bouton dédié modifie la couleur de l’arrière-plan du layout principal, également en cycle.

Changer le texte affiché : l’utilisateur peut entrer un texte dans le champ prévu, puis cliquer sur le bouton pour remplacer le message affiché au centre de l’écran.

L’application utilise :

ConstraintLayout pour la mise en page

TextView, EditText et Button comme composants principaux

ContextCompat pour gérer les couleurs

des listes de couleurs et des index cycliques pour permettre les changements successifs

Ce projet illustre la gestion des événements (setOnClickListener), la manipulation des vues avec findViewById, ainsi que l’utilisation basique des ressources (colors.xml).

### App Walk-though
`TODO://` Add the URL to your animated app walk-though `gif` in the image tag below. Make sure the gif actually renders and animates when viewing this README. (☝️ Remove this paragraph after after adding gif)

<img src="![CodePath_Gif](https://github.com/user-attachments/assets/5b1d8c31-2be9-4267-998f-188fae67f318)
" width=200><br>

`TODO://` In the User stories section below, add an `x` between the `-[ ]` like this `- [x]` for any user story you complete. (☝️ Remove this paragraph after after checking off user stories)

### Required User Stories
- [ ] 1. User sees custom text in a label - Hello from {name}!
- [ ] 2. User see's custom background color.
- [ ] 3. User can tap a button to change the text color of the label.

### Optional User Stories
- [ ] 1. User can tap a button to change the color of the background view.  
- [ ] 2. User can tap a button to change the text string of the label - Android is Awesome!  
- [ ] 3. User can tap on the background view to reset all views to default settings.  
- [ ] 4. User can update the label text with custom text entered into the text field.  
   - [ ] a. User can enter text into a text field using the keyboard.  
   - [ ] b. User can tap the "Change text string" button to update the label with the text from the text field.  
   - [ ] c. If the text field is empty, update label with default text string.  
