# AFUP Poitiers : 12/12/2017  - Docker : pour éviter le célèbre "Ca marche chez moi pourtant !!"

#### illustration avec 4 containers qui lancent des images différentes de php



- Pour lancer les containers : `docker-compose up -d`
- Pour les arrêter : `docker-compose down`
- Dans www/ se trouve un fichier phpinfo.php qui contient..... phpinfo()
- Lors de la première éxécution de `docker-compose up -d`, les images seront téléchargées puis installées sur votre machine.
- Pour ouvrir firefox et consulter les 4 containers qui pointent tous vers le même fichier sur des ports différents : `sh firefox.sh`

- [https://www.docker.com/what-docker](https://www.docker.com/what-docker)
