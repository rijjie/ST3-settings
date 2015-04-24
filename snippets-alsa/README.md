sublime-snippets
================

HTML CSS Sublime Text snippets


-----------

Liste de snippets (mis à jour régulièrement par Raphaël Goetter) à télécharger ici :
http://kiwi.gg/snippets 

-----------

Copier les fichiers sur votre disque à cet endroit : 

    C:\Users\*****\AppData\Roaming\Sublime Text 2\Packages\User

-----------

Raccourcis (fonctionnent avec la touche <kbd>Tab</kbd>) :
* @media + <kbd>tab</kbd> → `@media (max-width: 640px) {}`
* media + <kbd>tab</kbd> → `@media (max-width: 640px) {}`
* <kbd>&</kbd> + <kbd>tab</kbd> → `& nbsp ;`
* content + <kbd>tab</kbd> → du contenu-type HTML (titre, navigation, paragraphes)
* css + <kbd>tab</kbd> → `< link rel="stylesheet" href="styles.css" media="all" >`
* doctype + <kbd>tab</kbd> → feuille HTML de base
* doctypemini + <kbd>tab</kbd> → feuille HTML miniature de base
* ie + <kbd>tab</kbd> → `< !--[if IE]> <![endif]-- >`
* ie7 + <kbd>tab</kbd> → `< !--[if lte IE 7]> <![endif]-- >`
* knacss + <kbd>tab</kbd> → version complète et à jour de KNACSS.css
* list + <kbd>tab</kbd> → crée une liste ul/li de 5 éléments
* lorem + <kbd>tab</kbd> → crée du texte schnapsum
* loremp + <kbd>tab</kbd> → crée 3 paragraphes de schnapsum
* nav + <kbd>tab</kbd> → crée une navigation HTML5
* noie + <kbd>tab</kbd> → `< !--[if !IE]><!--> <!--<![endif]-- >`
* unicode + <kbd>tab</kbd> → affiche une liste de caractères unicode utiles
* viewport + <kbd>tab</kbd> → `< meta name="viewport" content="width=device-width,initial-scale=1.0" >`

Vous utilisez Emmet ?
=====================

Si vous utilisez le plugin Emmet (ex-zencoding), celui-ci risque de surpasser certains snippets de cette liste.

Pour éviter ce désagrément, modifiez le fichier User de Emmet.sublime-setting et ajoutez ce contenu :

    {
        "disabled_single_snippets": "@media media content css doctype doctypemini ie ie7 knacss list lorem loremp navi noie unicode viewport lien image"
    }
    
# Vous écrivez en Markdown ?

Voici quelques snippets dédiés :
* image + <kbd>tab</kbd> → `![alt](/path/$0 "title")`
* lien + <kbd>tab</kbd> → `[name](url)`
