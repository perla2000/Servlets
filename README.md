# Servlets
Le but de ce projet est d'écrire un programme	Java déployé côté serveur	Web et permettant	de	créer	des	pages	web	dynamiques, exécutés	par	un	"moteur"	de	servlet	qui celui ci sera désignés	par	une	URL.

## 1- Télécharger et installer le serveur Web Apache Tomcat
  J'ai telechargé le serveur Apache Tomcat version 8.5 qui est compatible avec la version de mon jdk (1.8) 
  
![tomcat](https://user-images.githubusercontent.com/88480955/152691101-a31e51db-0355-4da1-b672-b52e15bf3ad9.PNG)
  
## 2- Configurer le serveur et le lier au IDE Eclipse for Web developers 

![2](https://user-images.githubusercontent.com/88480955/152693440-aa96d24f-ab0b-4785-8f96-82cbc872e2cb.PNG)

  
## 3.1- Créer dans le "source file" un fichier java qui contiendra le code du servlet (il rendra un code HTML statique ) 

Voici le code du servlet

![dynamique](https://user-images.githubusercontent.com/88480955/152692176-d1cb9cd5-3dbf-4935-b37f-c87054e25f79.PNG)


### Le déploiement du servlet donne le résultat suivant sur le browser:

![res](https://user-images.githubusercontent.com/88480955/152693388-ace48bcd-df47-4a67-8a93-7cb8422d02a7.png)

## 3.2-Créer une page html (dans le folder webapp) qui contient un lien vers le servlet

![test1](https://user-images.githubusercontent.com/88480955/152692522-169b04e4-5d0f-4002-9927-4d93d1c1ec17.PNG)

Cette page HTML permet d'afficher sur le browser les inputs pour insérer le nom et le prénom 
et en cliquant sur le bouton Envoi ca nous dirige vers le Servlet
Voici le nouveau code du servlet pour récuperer les paramètres:

![test2](https://user-images.githubusercontent.com/88480955/152693001-f6450c94-1de0-4199-867f-73fa84fc0875.PNG)

## Résultat:
l'execution du fichier input.html qui se trouve dans le folder webapp nous donne l'affichage suivant:

![res1](https://user-images.githubusercontent.com/88480955/152693899-2f613a52-0f17-4adf-be8b-b0c90653d40c.PNG)

![res2](https://user-images.githubusercontent.com/88480955/152693907-2ad82c58-b3c4-42d5-8491-6355c0bb447f.PNG)


