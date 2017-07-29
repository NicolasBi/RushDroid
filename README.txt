Propositions d'implementations :
 * Ajouter une fonction de pause qui bloque la vue du puzzle mais arr�te le temps.
 * Implementer des achievements et la possibilit� de se connecter au Google play pour synchroniser ses achievements.
 * Ajouter des boutons pour nous suivre sur les reseaux sociaux (g+ facebook twitter).
 * Ajouter des boutons pour nous envoyer des dons.
 * Ajouter une animation de chargement et une animation de changement d'activit� (avec un glissement).
* Convertir les scores en long int au lieu de int pour eviter un depassement de capacit�.
* J'ai fait des recherches et commenc� � ecrire plusieurs pseudo-algorithmes pour faire un solveur et pouvoir implementer une fonctionnalit� de cr�ation de niveau ainsi que d'obtenir les coups minimaux pour chaque puzzle. 

Bugs � corriger :
 * Probl�me d'affichage que j'ai """resolu""" comme je le pouvais. Il se produit sur l'activit� Jeu enn mode landscape sur les tablettes, lorsqu'on lance l'application en mode portrait puis qu'on passe en mode landscape sur le jeu. Le canvas etait coup� vers le bas, il est maintenant surelev�. Je suppose que ce probl�me d'affichage est du � le pr�sence de Navbar mais je n'en suis pas sur.
 * Utiliser un service pour lancer/couper la musique ? Car elle se coupe un peu entre les activit�s
* J'ai ajout� le jour du rendu des boutons undo et restart. Restart fonctionne correctement, mais undo fait buguer le jeu. De plus, je ne suis pas satisfait de leur apparence.

Fonctionnalit�s qui peuvent vous echapper:
* L'application est par d�faut, entierrement en anglais. Des traductions fran�aises, espagnoles et turques se chargeront automatiquement selon la langue du telephone de l'utilisateur.
* L'application se trouve en ligne sur le play store sous le nom de "RushDroid" avec pour nom de soci�t� "Bizzozz�ro Nicolas". Sa page contient une traduction en anglais et en fran�ais ainsi que plusieurs captures d'ecrans. L'avis de certains utilisateurs m'a permis de me tenir au courant de plusieurs bugs d'affichage qui ont �t� corrig�s par la suite, et j'ai ajout� une fonctionnalit� supplementaire (le bouton suivant sur l'activit� de fin de jeu) suite � la demande d'un utilisateur.
* L'application ne peut volontairement pas �tre install�e sur les Android Watch (croyez-moi, c'�tait tr�s moche).

Commentaires supplementaires :
* J'ai corrig� le plus de warnings (indiqu�s par AndroidStudio) possibles
* Je n'utilise aucune ressource trouv�e sur internet sans en cr�diter son auteur et sans m'�tre assur� qu'elles �taient libres de droits
* Je n'ai pas r�ussi � utiliser l'API GooglePlay pour pouvoir permettre aux joueurs d'utiliser un classement et des achievements. Toutefois, les classements et achievements ont deja �t� cr��s sur mon compte Google Developer et j'ai recup�r� leur ID.
