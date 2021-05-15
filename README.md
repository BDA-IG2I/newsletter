# newsletter

L'objectif c'est pas d'avoir du beau code, c'est d'avoir une belle page.

## Envoyer la newsletter avec Zimbra
Pour envoyer la newsletter à partir de Zimbra il est nécessaire d’avoir recours à quelques subterfuges étant donné que le logo de la newsletter n’est pas host sur un serveur.
- Créer un nouveau mail Zimbra ;
- Joindre le logo dans le mail ;
- Ouvrir le code source ;
- La référence cid de l’image (il s'agit du contenu de la balise src) s'affiche, elle est propre à ce mail. Il sera nécessaire de remplacer la source de la balise image du logo dans le fichier HTML original de la newsletter par cette nouvelle source lorsque vous mettrez le code source complet dans le mail.

(soon le logo sera host quelque part, mais en attendant il faut faire ça)
