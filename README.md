1 - Créer un fichier json contenant entre 3 et 5 utilisateurs
Utilisateur: ID, nom, prénom, photo, adresse email et mot de passe

2 - Créer une page index.html qui contient
un bandeau horizontal vide
un formulaire contenant les champs “email” et “mot de passe” ainsi qu’un bouton de type div class=bouton,
contenant le texte “connexion” et une div permettant d’afficher un message d’erreur ou d’informations.

3 - Créer un template:
profil.tpl qui contient un squelette type pour l’affiche des informations d’une personne
(photo + nom + prénom + adresse e-mail) + un bouton “fermer”

4 - Lorsqu’un utilisateur rempli le formulaire de connexion, le bouton “connexion” 
reste gris (et inutile) tant qu’il n’y a pas au moins un caractère (différent de espace) dans les champs login et mot de passe.

5 -  Sinon, le bouton de connexion est “cliquable” et la combinaison “email + mot de passe” doit être cherchée dans le fichier
 json. Si l’utilisateur n’est pas trouvé, indiquez un message d’erreur. Sinon, l’utilisateur est “connecté”, indiquez “Bonjour “ 
suivi du prénom dans le bandeau horizontal, ainsi que les boutons “mes photos”, “ma galerie” et “Quitter”

6 - Si il clique sur son prénom, un pop-up apparait, faisant appel au fichier “profil.tpl” qui contient les infos de l’utilisateur

7 - Créez 2 fichiers json:
un fichier photos.json contenant des photos: id, titre et photo et id de l’utilisateur qui a enregistré la photo
un fichier partage.json contenant l’id de chaque photo lié soit à un ou plusieurs utilisateurs, soit lié à “*” qui représente TOUS les utilisateurs

8 - Lorsque l’utilisateur clique sur “Quitter”, il revient à la page principale de connexion et il lui est impossible de revoir son 
espace sans se reconnecter

9 - “mes photos” >> voir la liste des photos que j’ai partagé
10 - “ma galerie” >>> voir toutes les photos qui sont partagées avec moi