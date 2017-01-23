# 1.1 Internet : concept et fonctionnement  


## 1.1.1 petite définition  

Internet est un terme un peu fourre tout servant à évoquer tout ce qui concerne le web, les systèmes de communication, ...    

Pour remettre les choses en place, **Internet** est l'ensemple des réseaux permettant la communication entre les **clients** (vous) et les **servers** (le site).    
Vous utiliser Internet tout les jours pour :  
- Allez surfer sur le web  
- Regarder vos mails *(note : quelqu'un utilise encore les mails ?)*    
- <s>DDOS les gens</s>    
- ...  

Toute ses utilisations nécéssites l'envoie et la récéption de **message** sur le réseaux, voyons donc comment cela marche :  

![internet protocol](https://loulou123546.github.io/coursICN/basic/client-server.png)  

Ici, le client à besoins d'une info (ex : votre flux facebook). Il envoie donc une requête au server (ex : facebook.com).  
Le server va lire la requête et revoyez la page sous forme de réponse directement au client (l'appli facebook) et la boucle est bouclée.  

## 1.1.2 les protocoles  

Alors soyons clair dès maintenant, les requêtes et les réponses ne sont que du vulgaire texte.  
Mais ce texte varie selon l'utilisation, car un mail, une musique et une page web ne corresponde pas à la même chose.  
Les pionniers d'internet se sont donc mis d'accord sur des règles pour chaque type de requête/réponse.  
Ce sont ces règles que l'on appelle des **protocoles**, parmit lequel :  

- HTTP*(S)* : ce qui nous intérresse, à savoir le web  
- SMTP/IMAP : pour les services de mail  
- FTP : sert principalement à envoyer et télécharger des fichier entre un server et un client  
- PING : initialement, il servait à tester si un server était connecté à internet, mais sert maintenant à DDOS les gens  
- ...

Vous pouvez trouver quel protocole vous utiliser en regardant en haut de la page, ou il est écrit :  
`https://loulou123546.github.io/coursICN/basic/internet/`, où `https` est le protocole.  

## 1.2.3 Le web  

On attaque enfin le web. Le web tel qu'on le connaît à était créer en 1989 dans un laboratoire du CERN.  
Il était destiné à permettre l'échange de données entre les chercheurs du monde entier.  
Depuis il est gérer par le **World Wide Web Consortium (W3C)**, retenez bien que le nom de **W3C** car il est important.  
En effet, c'est eux qui décide des règles pour le web, à savoir ce nous apprendrons dans le chapitre suivant sur le **HTML**.   
