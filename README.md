# tp4

# Etape 2
 
Avec le logiciel Postman, sans préciser de paramètre supplémentaire, essayez d’accéder aux 
end-points http://localhost:3000/secu et http://localhost:3000/dmz.  

![image](https://github.com/user-attachments/assets/c48ca010-151a-4162-8588-efa380f9412b)
![image](https://github.com/user-attachments/assets/9ea67f12-c0e3-4b16-bfb1-ae4a58ed6b81)

A l’aide du site https://www.base64encode.org/fr/, effectuer l’encodage des identifiants de 
connexion tels qu’ils sont attendus. Dans l’onglet Headers de Postman, ajouter la clé 
BUT informatique – R6.A.05 – Développement Avancé – Semaine 4  
1 
laurent.giustignano@u-paris.fr 
Authorization et placer la valeur obtenue en base64, précédé de la mention Basic. Retester 
ensuite les end-points. 
¨ Pour simplifier l’utilisation, décocher cette clé nouvellement créée. Dans l’onglet Authorization, 
choisissez Basic Auth et remplissez les valeurs en claires. Vous observerez que le Header est 
automatiquement complété avec la bonne valeur. Retester ensuite les end-points et confirmer 
aussi qu’une erreur dans la saisie du username/password rejette l’authentification. 

![image](https://github.com/user-attachments/assets/7db81acc-eacc-48e7-bd0b-dfcd92457970)

On reteste ensuite les end-points et on confirme bien qu'une erreur dans la saisie du
username/password rejette l'authentification ("winee" au lieu de "wine").

Déterminer maintenant le rôle de la fonction after() pour la déclaration de la route '/secu'. 
¨ Dupliquer le code de route '/secu' pour créer la route '/autre' à l’intérieur de after(), mais elle 
doit être accessible sans authentification. 

C'est particulièrement utile quand on a besoin d'être sûr que toutes les fonctionnalités d'un plugin sont disponibles avant de les utiliser. 
Sans .after(), on risquerait d'essayer d'utiliser des fonctionnalités qui ne sont pas encore prêtes.

<img width="416" alt="image" src="https://github.com/user-attachments/assets/a6c6afaf-5f9c-489c-bf76-4d18f85e1282" />


# Etape 2

on crée une nouvelle clé,
et on signe la commande, puis nous testions sur postman pour voir si tout est bon :

![image](https://github.com/user-attachments/assets/5427b735-4554-44ff-be0f-d5b4ec084a8f)

![image](https://github.com/user-attachments/assets/0eaf907d-f90a-414c-bee2-cbe63fedf52a)

![image](https://github.com/user-attachments/assets/a19fe47d-50e1-44ce-9951-0ea615ad3201)




