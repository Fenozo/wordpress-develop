# wordpress-develop
WordPress Develop, Git-ified. Synced from git://develop.git.wordpress.org/, including branches and tags! This repository is just a mirror of the WordPress subversion repository. Please do not send pull requests. Submit patches to https://core.trac.wordpress.org/ instead. 


Documentation tout sur wordpress 
https://wabeo.fr/lire-code-wordpress/

# Quelques fichiers intéressants

Je le répète : le mieux pour comprendre le code de WordPress est de s’intéresser aux fichiers en rapport avec un de vos projets en cours. Cependant si vous avez trop hâte de plonger dans le bain, que vous avez envie de lire des fichiers particulièrement intéressants, en voici quelques-uns :

    #-- wp-includes/formatting.php et wp-includes/default-filters.php
    Le premier fichier contient les fonctions de nettoyage et de vérifications de chaines. Le second applique ces fonctions via des filtres sur de nombreux éléments de WordPress
    -- wp-includes/functions.php
    C’est un peu le « tout-venant » des fonctions super utiles de WordPress
    #-- wp-includes/query.php
    J’en ai déjà brièvement parlé, c’est le fichier qui contient la class WP_Query. En lisant ce fichier vous trouver pleins de méthodes pour personnaliser le chargement des contenus dans la boucle
    #-- wp-includes/class-wp.php
    Si vous souhaitez comprendre comment « démarre » WordPress du parse_request au query_vars en passant par les routes
    wp-includes/general-template.php et wp-includes/post-template.php
    Ces deux fichiers vous permettront de comprendre ce que font les fonctions que vous utiliser partout dans vos templates 😉
