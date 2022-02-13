# SeleniumGrid4
Execution et test du selenium Grid 4 sous python
Pour démarrer avec selenium grid 4 

Télécharger le serveur selenium Grid depuis le site officiel ::
https://www.selenium.dev/downloads/

Télécherger le driver du navigateur exemple (google chrome :: https://chromedriver.chromium.org )
Ajouter l'emplacement du chrome driver  à la variable PATH de votre machine vous pouvez suivre les étapes décrites dans ce site 
https://sysreseau.net/ajouter-repertoire-path-sous-linux/
 
Executer les comandes si desous ::
  java -jar selenium-server-<version>.jar hub
  java -jar selenium-server-<version>.jar node
 
 Enfin si tout va bien vous vous pouvez consulter la liste de vos noeds via un lien de ce genre  http://<votre Ip>:4444/
