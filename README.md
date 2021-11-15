
## Base de données 

php artisan migrate
php artisan db:seed

![blogBD](https://user-images.githubusercontent.com/59780119/141789658-cf50623b-dc1d-4853-8cd7-e15a45285b6c.PNG)


## Routes
#Formations:
- **['/']** Page d'acceuil, liste des formations
- **['/trainings/add']** Rédiger et ajouter une formation 
- **['/trainings/{id}']** Affiche les détails d'une formation selon son identifiant
- **['/trainings/{id}/update']** Mettre à jour une formation selon son identifiant
- **['/trainings/{id}/update/picture']** Mettre à jour l'image d'une formation selon son identifiant
- **['/trainings/{id}/delete']** Supprime une formation selon son identifiant

#Commentiares:
- **['/comment/{training}']** Ajouter un commentaire à une formation selon son identifiant
- **['/comment/delete/{id}']** Supprimer un commentaire à une formation selon son identifiant

#Catégories:
- **['/categories']** Affiche toutes les catégories
- **['/categories/add']** Ajouter une catégorie
- **['/categories/{id}/update']** Mettre à jour une catégorie selon son identifiant
- **['/categories/{id}/delete']** Supprimer une catégorie selon son identifiant 

#Mails:
- **['/contact']** Envoyer un mail pour prendre contact avec l'administrateur du site
- **['/register/update/{email}']** Envoie un mail à l'administrateur lors de la demande d'inscription d'un nouvelle utilisateur

#Authentification:
- **['/login']** S'authentifier
- **['/logout']** Se déconnecter
- **['/register']** Formulaire d'incription
- **['/verify-email']** Verification du mail du nouvelle utilisateur
