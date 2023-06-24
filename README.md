#  Projet Spring Angular JWT , Digital Banking



###     A propos du projet
Ce projet vise à créer une application permettant de gérer des comptes bancaires pour les clients. Il y a deux types de compte, les comptes courants et les comptes épargnes, sur lesquels peuvent être effectuées des opérations de type **DEBIT** ou **CREDIT**. 

### Les étapes de projet
<ul>
<li> Pratie 1  : <a href="https://www.youtube.com/watch?v=muuFQWnCQd0">Couche DAO</a></li> <br>
1. Créer un projet Spring Boot<br>
2. Créer les entités JPA : Customer, BankAccount, Saving Account, CurrentAccount, AccountOperation<br>
3. Créer les interfaces JPA Repository basées sur Spring Data<br>
4. Tester la couche DAO<br><br>

<li> Partie 2 : <a href="https://www.youtube.com/watch?v=PTI8cniOXLc">Couche service, DTOs et RestController</a></li>

pour Swagger, avec Spring boot 3 voici la dépendance à utiliser :

```
<dependency> 
   <groupId>org.springdoc</groupId> 
   <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId> 
   <version>2.1.0</version> 
 </dependency
 ```


<li>Partie 3 et 4 :</li>  
Client Angular : <a href="https://www.youtube.com/watch?v=bOoPKctcE0s">Lien 1</a>
                  <a href="https://www.youtube.com/watch?v=bOoPKctcE0s">Lien 2</a>
</ul>

  
                 
## I-  Voici une vidéo explicative

<video src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/508b2d11-57a7-4fe0-b60d-64bdc6d3bd29"></video>

## II- Les Différentes pages d'exécution
  ##### 1. L’affichage de la liste des clients avec leur ID,Name et EMAIL .
  <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/695e897f-cc1b-43c9-99a9-bacec6d91ea0" width="">
  </div>
  
  ##### 2. L’ajout d’un nouveau customer .
   <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/9cd12ce4-c1d7-45c5-94fe-542401a836b6" width="">
  </div>
  
   #####  3. La suppression de customer .
   <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/9cd12ce4-c1d7-45c5-94fe-542401a836b6" width="">
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/8cd0029c-4161-4274-85df-c5a6cb1d8b55" width="">
  </div>
 
   #####  4. L’apparition des informations du client Yassine en appuyant sur le bouton en vert « ACCOUNTS »
  <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/cb514187-65c4-43d0-92bf-698fc014c5fa" width="">
  </div>
  
   #####  5. La recherche du client par le Keyword :h
<div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/7ba945ba-7ca2-462a-b81c-ba7bb4e2e0cd" width="">
  </div>

  #####  6.La recherche du compte par son ID et l’affichage des opérations dont il a été subit en indiquant la DATE , le type d’opération et le montant .
   <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/bc41d937-2945-4788-9451-bdb19756d6eb" width="">
  </div>

 #####  7. Débiter le compte par un montant de 1000 mentionné dans la description.
 <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/59aad0f3-21b6-4ce3-93bd-14e7016fac44" width="">
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/5705dc83-f506-471d-9279-039f9c0074fb" width="">
  </div>

 #####  8. Créditer le compte d’un montant de 5000 mentionné dans la description.
 <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/aaa39bfe-65c8-4e70-97f1-e36d3b0db595" width="">
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/4ee48722-c7f5-43ed-a2b4-109893c8600f" width="">
  </div>

 #####  9.Effectué un transfert d’argent D’un montant de 120 mentionné dans la description, du compte actuel vers un compte destinataire en mentionnant son ID .
 <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/1c4c2a2d-932e-4e44-b439-573443be6b5b" width="">
  </div>
  
 #####  10.L’apparition de la nouvelle opération débiter dans la liste des opérations dont il a subit le compte destinataire.
 <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/63f772d0-ccbf-476c-81c4-eabf2281a32a" width="">
  </div>
  
 #####  11.L’apparition de la nouvelle opération créditer dans la liste des opérations dont il a subit le compte actuel .
 <div>
    <img src="https://github.com/Oussama-pro/Activit-Pratique-N-5-Projet-Spring-Angular-JWT-Digital-Banking/assets/98102335/1d7cfc3d-570b-4909-a5bb-67a0623ed8a4" width="">
  </div>
 
  




