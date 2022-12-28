# NF19_Projet
Projet de NF19 pour partage un site wordpress pré-configurer en utilisant Docker


Pour commencer vous devez télécharger et installer docker :

- https://docs.docker.com/desktop/install/windows-install/

Ensuite vous devez rélécharger les documents nécéssaires. Pour ce faire, cliquez sur le bouton vert en haut a droite avec écrit "Code" dessus. 
Puis, cliquez sur "Download as Zip", et décrompressez l'archive là où vous souhatez.




Allez dans ce dossier décompréssé et lancez un Terminal dans ce dossier. 

Une fois dans ce dossier avec votre Terminal, executez la commande :
- docker compose up -d


Wordpress et MySQL s'installeront dans des containers Docker. Les données de la BDD ainsi que les images sauvegardées seront respectivement sauvegardée dans les dossier "GIFTCARD_SQL" et "wordpress" du dossier décompressé. Ainsi, pour partager vos modifications, il suffit de transférer a vos collégues votre dossier global.

