# Lexique Markdown

  - <ins>Titres</ins>
        - On utlisera le symbole \# pour declarer un titre. le nombre de \# joue sur la "profondeur du titre"
  - <ins>Images</ins>
        - L'integration des images est semblable a une balise img en html. On peut d'afficher une image selon le theme
        exemple : 
        \<picture>
          \<source media="(prefers-color-scheme: dark)" srcset="url de l'image">
        \<source media="(prefers-color-scheme: light)" srcset="url de l'image">
        \<img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="url de l'image">
      \</picture>
        l'url de l'image peut être soit une adresse url, soit un chemin relatif par rapport au repos
  - <ins>Listes</ins>
        - on peut creer des listes non triées avec les symboles  - * +, ou des nombres pour des listes triées.
        Possibilité de creer des listes imbriquées soit avec la touche tab pour les editeurs qui le permettent , soit en 
        ajoutant un nombre d'espace manuellement
  - <ins>Formatage</ins> de texte (italique, souligné, gras)
    * \*\* \*\* ou \-\- \-\- texte en **gras**
    * \* \* ou \_ \_ texte en *italique*
    * \~\~ \~\~ ~texte ~barrré~
    * \*\* \*\* et \_ \_  **gras et _italique_ imbriqués**
    *  \*\*\* \*\*\* ***tout en gras et italique***
    * \<sub> \<\sub> <sub>indice</sub>
    * \<sup> \<\sup> <sup>exposant</sup>
    * \<ins> \<\ins> <ins>texte souligné</ins>
  - <ins>Code</ins>
    * pour citer du code, le placer entre deux triple backstick ``` ceci est du code```
  - <ins>Citations</ins>
    * citation de texte avec : \>
  - <ins>Tableaux</ins>
  - <ins>Liens</ins>
      * Pour creer un lien inline on place le texte entre crochets\[\] et l'url du lien entre parenthèses \(\)
      * example: pour voir un exemple de tableux voir \[ ce lien \]\(https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github#ajout-dun-tableau\)
