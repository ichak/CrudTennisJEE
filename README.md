# **Projet Tennis**
Le projet Tennis est un projet d'étude d'une base de données relationnelle pour stocker des informations sur les matchs de tennis, les joueurs, les épreuves et les tournois. La base de données comprend plusieurs tables interconnectées, permettant de stocker des informations détaillées sur les matchs de tennis et les joueurs, ainsi que les épreuves et les tournois auxquels ils ont participé.

# **Fonctionnalités CRUD**
Le projet Tennis propose des fonctionnalités CRUD (Create, Read, Update, Delete) pour gérer les données de la base de données. Voici un aperçu de ces fonctionnalités:
1. **Create**
- Créer un nouveau joueur dans la table JOUEUR  
- Créer un nouveau tournoi dans la table TOURNOI
- Créer une nouvelle épreuve dans la table EPREUVE
- Créer un nouveau match de tennis dans la table MATCH_TENNIS  
2. **Read**  
- Afficher la liste de tous les joueurs dans la table JOUEUR
- Afficher la liste de tous les tournois dans la table TOURNOI
- Afficher la liste de toutes les épreuves dans la table EPREUVE
- Afficher la liste de tous les matchs de tennis dans la table MATCH_TENNIS
- Afficher les détails d'un joueur spécifique à partir de son ID dans la table JOUEUR
- Afficher les détails d'un tournoi spécifique à partir de son ID dans la table TOURNOI
- Afficher les détails d'une épreuve spécifique à partir de son ID dans la table EPREUVE
- Afficher les détails d'un match de tennis spécifique à partir de son ID dans la table MATCH_TENNIS  
- Afficher le nom du tournoi, le type d'épreuve, l'année de l'épreuve, le nom du vainqueur et le nom du finaliste pour un match de tennis spécifique à partir de son ID
3. **Update**
- Mettre à jour les informations d'un joueur spécifique à partir de son ID dans la table JOUEUR
- Mettre à jour les informations d'un tournoi spécifique à partir de son ID dans la table TOURNOI
- Mettre à jour les informations d'une épreuve spécifique à partir de son ID dans la table EPREUVE
- Mettre à jour les informations d'un match de tennis spécifique à partir de son ID dans la table MATCH_TENNIS  
4. **Delete**
- Supprimer un joueur spécifique à partir de son ID dans la table JOUEUR, ainsi que tous les matchs de tennis associés dans la table MATCH_TENNIS et tous les scores associés dans la table SCORE_VAINQUEUR
- Supprimer un tournoi spécifique à partir de son ID dans la table TOURNOI, ainsi que toutes les épreuves associées dans la table EPREUVE et tous les matchs de tennis associés dans la table MATCH_TENNIS et tous les scores associés dans la table SCORE_VAINQUEUR
- Supprimer une épreuve spécifique à partir de son ID dans la table EPREUVE, ainsi que tous les matchs de tennis associés
