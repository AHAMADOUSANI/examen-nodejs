git clone //pour cloner un projet
git init :: pour initialiser le depot
git remote pour connecter ou relier le projet au repository git creer
git add pour ajouter notre projet
git -m commit pour creer une image de notre projet
git branch creer une branche pour notre projet
git push pousser notre projet vers le repot git
// creation de dockerfile
docker build -d nom_image . pour creer une image
docker ps // voir les images existantes
docker run --p -d 3000:3000 nom-image // lancer un conteneur en arriere plan
docker ps voir les conteneurs existants

// creation de docker-compose 
docker-compose ps //voir le log des conteneurs
docker-compose up -d pour faire tourner les conteneurs en tache de fond
docker-compose logs nom-conteneur verification du fonctionnement d'un conteneur
