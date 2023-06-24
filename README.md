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

<video src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/2d927771-214e-481c-ab6c-52e67492e43f"></video>

## II- Les Différentes pages d'exécution
  ##### 1. L’affichage de la liste des clients avec leur ID,Name et EMAIL .
  <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/e64f4ed6-9732-48d2-b774-a7df004f52b8" width="">
  </div>
  
  ##### 2. L’ajout d’un nouveau customer .
   <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/eb707235-3df8-4b4d-ab92-b653107abf29" width="">
  </div>
  
   #####  3. La suppression de customer .
   <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/c5c62385-bd7c-46f9-af40-89834e9a9c26" width="">
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/699f4c4d-6c74-4338-bbd2-307ff8470902" width="">
  </div>
 
   #####  4. L’apparition des informations du client Yassine en appuyant sur le bouton en vert « ACCOUNTS »
  <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/da478067-6573-4391-b3bd-f915deef4aed" width="">
  </div>
  
   #####  5. La recherche du client par le Keyword :h
<div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/e5c5fa23-bdc7-4816-b6c1-109ad4442e98" width="">
  </div>

  #####  6.La recherche du compte par son ID et l’affichage des opérations dont il a été subit en indiquant la DATE , le type d’opération et le montant .
   <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/b9ee7850-c4d0-4af8-9ff5-1fa9929d8c11" width="">
  </div>

 #####  7. Débiter le compte par un montant de 44 mentionné dans la description.
 <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/934fc709-216b-44cf-90a5-0ff786a5d369" width="">
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/7808a8ec-97ac-4167-ae83-9c3a7a5ac4a6" width="">
  </div>

 #####  8. Créditer le compte d’un montant de 5000 mentionné dans la description.
 <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/69da042d-7089-40f5-a380-fa57fd38658e" width="">
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/bce964ac-e944-4f79-8dbb-b643997ec240" width="">
  </div>

 #####  9.Effectué un transfert d’argent D’un montant de 120 mentionné dans la description, du compte actuel vers un compte destinataire en mentionnant son ID .
 <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/f192eb07-bf67-4f68-8871-7ecc19323abb" width="">
  </div>
  
 #####  10.L’apparition de la nouvelle opération débiter dans la liste des opérations dont il a subit le compte destinataire.
 <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/2b9aa2c7-5441-49a7-980c-5814e112562d" width="">
  </div>
  
 #####  11.L’apparition de la nouvelle opération créditer dans la liste des opérations dont il a subit le compte actuel .
 <div>
    <img src="https://github.com/Oussama-pro/digital-banking-printemps-backend/assets/98102335/b3c9fd3a-4890-43b1-bc3f-6ee1633c24a1" width="">
  </div>
 
  




