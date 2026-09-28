# TP 2 : Persistence des données avec JPA, Hibernate et H2

Ce projet est une application Java démontrant la mise en œuvre de la persistance des données avec **JPA (Java Persistence API)**, **Hibernate** et une base de données en mémoire **H2**. Il intègre la gestion d'opérations CRUD génériques, des validations sur les entités ainsi que des tests unitaires complets.

---

##  Structure du Projet

```text
TP2_HIBER_ENTITE
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           ├── App.java                   # Classe principale d'exécution
│   │   │           ├── model                      # Entités JPA avec annotations de validation
│   │   │           │   ├── Salle.java
│   │   │           │   └── Utilisateur.java
│   │   │           └── service                    # Services et opérations CRUD
│   │   │               ├── AbstractCrudService.java
│   │   │               ├── CrudService.java
│   │   │               ├── SalleService.java
│   │   │               └── UtilisateurService.java
│   │   └── resources
│   │       └── META-INF
│   │           └── persistence.xml                # Configuration JPA / Hibernate / H2
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── service                    # Tests unitaires JUnit
│                       ├── SalleServiceTest.java
│                       └── UtilisateurServiceTest.java
├── pom.xml                                        # Dépendances Maven
└── README.md
```


https://github.com/user-attachments/assets/ffed4b07-aa0b-4cac-b28d-d1e2b9305c0c



