# Guide d'usage

## Couleurs principales
Les couleurs principales permettent de définir les couleurs principales que aura ton thème Vencord. Voici les variables à modifier pour :

```--primary-color``` : Pour modifier la couleur principale ( notification & nouveau message)

## Modifier le fond d'écran
Pour modifier le fond d'écran, il faut modifier la variable "--background" dans :root et indiquer un chemin d'image.

*Exemple :* 
```css
    --background: url('https://www.global-esports.news/wp-content/uploads/2025/06/REPO-12.jpg');
    --background-transparency-low: rgba(0, 0, 0, 0);
    --background-transparency-high: rgba(0, 0, 0, 0.5);
```
Sur cette exemple, ``--background-image`` est pour l'image de fond, ``--background-transparency-low`` est pour rendre transparent le fond, et ``--background-transparency-high`` est pour rendre transparent les menus et cadres.

## Font & Text
C'est section est réservé à la modification de text, ect. Voici les listes des variables disponibles

``--text-default`` : Modifie la couleur du texte des messages.

``--chat-text-muted`` : Modifie la couleur des textes petits.

``--general-text`` : Modifie l'ensemble des textes ( salons, mp, activité, pseudos, ect ; Par défault : ``gray``).

``--channels-default``: Modifie l'ensemble des textes d'activité et rôle de serveur.

*Exemple de configuration de base pour fond sombre :*
```css
    /* Font & Text */
    --text-default: white;
    --font-default: rgb(59, 59, 59);
    --chat-text-muted: gray;
    --general-text: white;
```

## TopBar
``--topbar-text`` : Pour modifier le text dans la topbar afficher avant le titre de la page.

``--topbar-color`` : Couleur tu titre ajouté à la topbar (Par défault : ``rgba(255,255,255,0.5)``)

*Exemple de configuration possible :*
```css
    --topbar-text: "Mon thème • by Me";
    --topbar-color: gray;
```