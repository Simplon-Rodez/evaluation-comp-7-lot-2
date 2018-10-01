# Créer un plugin Wordpress
Il vous est demandé de créer un plugin Wordpress permettant d'ajouter (via le back-office) et de lister des partenaires dans une page.

## Objectifs
* **Savoir utiliser un CMS.**  
    Durée estimée : *2 jour*  
    Compétence : *7 Mettre en oeuvre une solution de gestion de contenu ou E-commerce (niv 3)*

## Réalisation :
**Durée :** 01 octobre 9h00 - 02 octobre 17h (tout retard ne sera pas corrigé)  
**Groupe :** En solo  
**Formalité d'envoi :** Dossier zippé envoyé par mail à Thomas Catinaud


## Rendu :
* Le code source

## Sujet
### Demande 
Créer un plugin "Partenaire".


### Contraintes
* **Créer un plugin "partners".**
* **Créer un custom post type partenaire DANS LE PLUGIN**. Ce contenu personnalisé devra contenir un titre et une image mise en avant (thumbnail). L'éditeur (WYSIWYG) n'est pas obligatoire.
* Le plugin ne doit **faire appel à aucun autre plugin**.
* Le code affiché se fera via un **shortcode** à coller dans la page désiré. Le shortcode s'appellera [partners]
* Dans le shortcode (côté template), les différents partenaires seront listés grâce à la méthode WordPress **WP_query**.

###Tips
* [Plugin](https://wpformation.com/creer-plugin-wordpress/)
* [Shortcode](https://codex.wordpress.org/Shortcode_API)
* [WP_query](https://codex.wordpress.org/Class_Reference/WP_Query)
* [Custom Post Type](https://codex.wordpress.org/Function_Reference/register_post_type)

## Critères de validation
* Utiliser des composants de type service web ou applicatif
* Installer une solution logicielle de type CMS ou e-commerce
* Prendre en compte les contraintes des applications multilingues
* Développer les gabarits de mise en page (template)
* Développer des modules complémentaires avec des composants serveurs