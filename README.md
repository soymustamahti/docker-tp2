# WORDPRESS

1. Assurez-vous que vous avez correctement installé docker avec docker-compose
2. Télécharger wordpress [ici](https://wordpress.org/download/)
3. Une fois qu'il a été téléchargé et extrait, il doit être placé dans le fichier `www`
4. Une fois que c'est fait, renommez le dosier `wordpress` en `html`, comme dans l'image suivante

<img src="./example.png" alt="html folder" width="300"/>

5. lLncer :
        ``` 
        docker-compose up -d 
        ```
6. Allez à http://localhost
7. Enjoy
8. Si vous voulez utiliser la base de données, vous renommé le ficher `wp-config-sample.php` a `wp-config.php` et utiliser les données d'environnement du service mariadb (dans le docker-compose.yml)

## Le point 8 n'est pas nécessaire