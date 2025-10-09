# Objectif
Il permet de selectionner les albums selon l'artiste et de donner l'ID de l'album et le prix.

# Pré requis
vsCode, GO, Terminal 

Tutorial: "https://go.dev/doc/tutorial/database-access"
configurer mariadb ou mysql.
    - se connecter
    - créer une database nommée "recordings"
    - se positionner sur la base recordings
    - executer le script create-table.sql

# Compiler
Compilation dans le répertoire courant:
    - "go build ."

# Executer

pour executer le programme il faut se connecter a une base de donnee pour cela il aut le login et la pasword de la base de donnée.
    - le login est trouvé dans la variable d'environnement DBUSER.
    - le password est trouvé dans la variable d'environnement DBPASS.

Pour executer il faut ouvrir un terminal et y écrire les deux variables suivantes avec derriere (go run .):
        "DBUSER=xxx DBPASS=xxx go run ."
