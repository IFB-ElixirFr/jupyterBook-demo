# jupyterBook-demo
Comment faire les premier pas avec un Jupyter book sur le cluster de l'IFB


## Objectifs

Lister les différentes commandes pour démarer un Jupyter book et comment le partager. 

**Note 1** 

Cette intro est réalisée sur le cluster de l'IFB pour vous éviter de devoir faire des instalations particulières. Par contre si vous le souhaitez par la suite, je peux aussi le faire via des dockers.


**Note 2** 

Pour des questions de simplicité, je fais cette démo sur GitHub pour l'héberger sur une GitHub pages. C'est aussi possible sur GitLab (qui viendra après). 

## Création d'un répo GitHub

Pas d'explication ici. Il faut que votre répo soit public par contre pour pouvoir mettre votre livre en ligne. N'oubliez pas la licence et un read me  :wink:

## Git clone sur le cluster

Pas d'explication ici non plus, normalement vous savez faire sinon (attention moment promotion !) l'IFB propose une formation pour ça `FAIR bioinfo`. 


## Création d'un book 

1. Chargement du module

```bash
module load jupyter-book
```

2. Création d'un book

```bash
jupyter-book create mynewbook/
```



## Ressource

- https://jupyterbook.org/en/stable/intro.html