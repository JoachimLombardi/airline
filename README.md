#  Projet airline


<a href=https://trello.com/invite/b/a3Owefoc/ATTIc0a5d38e0be81d7f220617fface7e416CA156689/application-plane> Kanban </a>


## Installation

Pour commencer, il faut cloner le repo Github avec cette commande : 


```sh
git clone https://github.com/PierreGia/airline.git
```

Apres avoir cloné le repo, il faut ensuite taper la commande :

```sh
pip install -r requirements.txt
```

Ensuite, il faut modifier les informations du dossier *config.py* dans le dossier *create_database* pour que l'adresse de la base de données, le nom de la base de données, le nom d'utilisateur, le mot de passe et le port correspondent à vos informations.

Puis, il faut exécuter le fichier *create_database.py* qui se trouve dans le dossier *components* pour créer la base de données.

Pour finir, vous pouvez lancer le fichier *app.py* en executant la commande suivante:

```py
streamlit run app.py
```

## Utilisation

En premier lieu vous devez vous inscrire via le formulaire d'inscription.
Ceci fait, vous devez vous connecter avec le login et le mot de passe que vous avez donné au préalable. 
Une fois connecté, vous avez accès au formulaire pour choisir différents paramètres et voir la prédiction du modèle (satisfait ou non) et avec quelle probabilité.
Vous pourrez également voir les statistiques du modèle.

