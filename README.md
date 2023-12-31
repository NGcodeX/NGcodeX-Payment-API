# [NGcodeX](https://ngcodex.com) Payment API
![montage NGcodeX](https://github.com/NGcodeX/NGcodeX-Payment-API/blob/main/.github/workflows/ngcodexPayementBanner.jpg?raw=true)

Bienvenue dans le référentiel de l'API de paiement pour le club étudiant NGcodeX. Cette API permet d'interagir avec les services de paiement Orange Money et MTN Money pour faciliter les transactions financières au sein de notre communauté.

## Fonctionnalités

- Intégration avec les API Orange Money et MTN Money.
- Gestion des transactions de paiement.
- Suivi des statuts des transactions.
- Sécurité renforcée avec HTTPS.

## Structure du Projet

Le projet suit une architecture MVC (Modèle-Vue-Contrôleur) pour une organisation claire du code :

- `model/` : Logique métier liée aux paiements.
- `view/` : Contrôleur gérant les requêtes HTTP et les réponses.
- `util/` : Classes utilitaires, notamment pour les appels HTTP.
- `exception/` : Gestion des exceptions liées aux paiements.
- `config/` : Configuration de l'API (clés, URLs, etc.).
```
src
|-- main
    |-- java
        |-- com
            |-- ngcodex
                |-- model
                    |-- PaymentService.java
                    |-- PaymentResponse.java
                |-- controller
                    |-- PaymentController.java
                |-- util
                    |-- HttpUtil.java
                |-- exception
                    |-- PaymentException.java
                |-- config
                    |-- ApiConfig.java
    |-- webapp
        |-- META-INF
            |-- MANIFEST.MF
        |-- WEB-INF
            |-- lib
                |-- [ NGcodeX JAR.. ]
            |-- views
                |-- index.jsp
                |-- payment.jsp
                |-- transactionHistory.jsp
                |-- error.jsp
                |-- success.jsp
                |-- layout.jsp
            |-- web.xml

```
## Comment Contribuer

Si vous souhaitez contribuer à l'amélioration de cette API, veuillez consulter notre guide de contribution dans le fichier CONTRIBUTING.md. Toutes les contributions sont les bienvenues !

## Exigences

- Java 8 ou version ultérieure.
- Serveur d'application Java EE (comme Apache Tomcat).
- - Java EE
- Servlets
- JSP
- IDE de votre choix. nous avons utiliser Eclipse

## Documentation

Consultez la documentation complète de l'API dans le dossier `docs/` pour des instructions détaillées sur l'utilisation de chaque fonctionnalité.

## Licence

Ce projet est sous licence MIT - voir le fichier LICENSE.md pour plus de détails.

Merci de soutenir le projet NGcodeX Payment API !
