# Projet WordPress pour projet Cartograhpie Créativité Québec

Ceci est le dépôt du projet WordPress pour le site web interactif de [Cartographie].

## Instructions pour les développeurs

1. Clone le dépôt.  https://github.com/martinroc/cartographieCQ.git
2. Configure WordPress localement.
3. Travaille sur ta branche de fonctionnalité.

### Conseil de comment gérer les branches pour chaque développeur.
1.	Chaque développeur crée sa propre branche :
Chaque membre de l'équipe doit créer une branche à partir de develop pour travailler sur une fonctionnalité spécifique. Par exemple :
    
    git checkout develop
    git checkout -b feature/nom-de-la-fonctionnalite

Remplace nom-de-la-fonctionnalite par une description courte de la tâche (par exemple, feature/header-design ou feature/contact-form).

2.	Travailler sur la branche :
Chaque développeur travaille sur sa branche et fait des commits réguliers :

    git add .
    git commit -m "Description des modifications"
    git push origin feature/nom-de-la-fonctionnalite

3.	Fusionner les modifications :
Une fois la fonctionnalité terminée, le développeur crée un Pull Request (PR) sur GitHub pour fusionner sa branche dans develop. Les autres membres de l'équipe peuvent alors examiner le code avant de l'accepter.

4.	Rester synchronisé :
Pendant que tu travailles sur ta branche, il est important de te synchroniser régulièrement avec develop pour éviter les conflits :

    git checkout develop
    git pull origin develop
    git checkout feature/nom-de-la-fonctionnalite
    git merge develop

________________________________________

Exemple de workflow pour l’équipe
•	Développeur 1 :

o	Branche : feature/header-design
o	Travaille sur le design de l'en-tête.

•	Développeur 2 :

o	Branche : feature/contact-form
o	Travaille sur le formulaire de contact.

•	Développeur 3 :

o	Branche : feature/seo-optimization
o	Travaille sur l'optimisation SEO.

Chacun travaille indépendamment sur sa branche, et toutes les modifications sont fusionnées dans develop une fois approuvées.
