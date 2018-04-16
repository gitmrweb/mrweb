# Intégration de la maquette Davril sur une page internet


## Solution 1 :
#### Intégration de la maquette avec compatibilité mobile/tablette
Si le site n'intègre pas une solution de redimensionnement de'iFrame

Copier le code ci-dessous dans la partie HTML de la page ou dans la partie "text" de l'éditeur de texte dans l'administration du site.

    <div style="position:relative;overflow:hidden;padding-top:56.25%;"><iframe src="https://maquette.epsilon3d.fr/davril/st-cyr/index.php" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;"></iframe></div>

----

## Solution 2 :
#### Intégration de la maquette sans compatibilité mobile/tablette
Si le site intègre déjà une solution de redimensionnement d'iFrame

Copier le code ci-dessous dans **la partie HTML** de la page ou dans **la partie "text"** de l'éditeur de texte dans l'administration du site.

    <iframe src="https://maquette.epsilon3d.fr/davril/st-cyr/index.php" frameborder="0"></iframe>
