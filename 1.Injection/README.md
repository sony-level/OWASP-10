

# 10 défis pour découvrir les dix principales vulnérabilités OWASP

Ces défis aident à comprendre les vulnérabilités web les plus courantes.
Vous mettrez la théorie en pratique en relevant ces défis.

Le Top 10 OWASP est un document de sensibilisation standard pour les développeurs et la sécurité des applications web. Il représente un consensus général sur les risques de sécurité les plus critiques pour les applications web.

https://owasp.org/www-project-top-ten/

## :dart: Défi d'injection

Ce défi vous permet d'apprendre la vulnérabilité d'injection.

```
Les failles d'injection, telles que SQL, NoSQL, OS et LDAP, se produisent lorsque des données non fiables sont envoyées à un interpréteur dans le cadre d'une commande ou d'une requête. 
Les données hostiles de l'attaquant peuvent tromper l'interpréteur pour exécuter des commandes non prévues ou accéder à des données sans autorisation appropriée.

```

## :hammer_and_wrench: Installation

```
# Cloner le référentiel Git contenant le projet OWASP-10 depuis GitHub
git clone https://github.com/sony-level/OWASP-10.git

# Accéder au répertoire OWASP-10 récemment cloné
cd OWASP-10/

# Accéder au sous-répertoire contenant la section "Injection" du projet
cd 1.Injection/

# Lancer les conteneurs Docker en utilisant Docker Compose
# --build : Construire les images Docker si elles n'existent pas déjà ou si elles ont été modifiées
# -d : Détacher les conteneurs Docker pour qu'ils s'exécutent en arrière-plan
docker-compose up --build -d

```
Maintenant, allez sur [127.0.0.1:8001](http://127.0.0.1:8001) et profitez-en.

![Interface](/home/kali/Musique/1.Injection/www/assets/images/Screenshot_20240213_131509.png)


