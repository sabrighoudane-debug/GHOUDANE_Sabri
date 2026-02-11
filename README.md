# Simulation Spatiale

![logo de la fusée](./images/rocket.png)

## Présentation

Ce projet a été réalisé par un groupe de **trois étudiants en Licence 2 Informatique**.

Il s'agit d'un logiciel de **simulation spatiale** permettant de modéliser le système solaire comme un support statique dans lequel les astres évoluent autour du Soleil, et d’exécuter différentes missions orbitales.

Ce projet s’inscrit dans la continuité de notre travail réalisé au **semestre 3**, où nous avions développé une application Java Swing permettant de générer des fichiers playlist à partir d’une interface graphique.

---

## Objectifs

- Modéliser un système solaire simplifié
- Implémenter des calculs orbitaux
- Simuler des missions spatiales
- Concevoir une architecture logicielle structurée
- Approfondir la programmation orientée objet

---

## Missions disponibles

Le logiciel permet d’effectuer trois missions principales :

### Mise en orbite basse terrestre (LEO)

- Simulation du décollage
- Calcul de la vitesse orbitale
- Stabilisation autour de la Terre

### Mise en orbite géostationnaire (GEO)

- Placement à 35 000 km d’altitude
- Synchronisation avec la rotation terrestre
- Maintien d’une position fixe relative à la surface

### Mission interplanétaire

- Calcul de trajectoire vers une autre planète
- Gestion du mouvement orbital des planètes
- Navigation et arrivée sur la planète cible

---

## Modélisation du système solaire

- Le Soleil est défini comme référentiel central fixe.
- Les planètes évoluent autour du Soleil selon leurs paramètres orbitaux.
- Le système solaire agit comme support statique de simulation.
- Les fusées et sondes interagissent dynamiquement avec cet environnement.

---

## Architecture du projet

Le projet suit une organisation modulaire inspirée du modèle MVC :

1. *model* : Objets métiers (Planète, Fusée, Sonde, Orbite…)
1. *view* : Interface graphique
1. *controller* : Gestion des interactions
1. *main* : Point d’entrée du programme

---

## Technologies utilisées

- **Exécution** : openjdk version "21.0.8" 2025-07-15
- **Compilation** : javac 21.0.8

---

## Exemple d'éxécution

```java
public class Main {
    public static void main(String[] args) {

        MainGUI simulationMainGUI = new MainGUI("Simulation");
    }
}
```
## Auteurs

### Lydia LACHEMOT
- Rôle : architecture,logique métier, contrôleur


### Thomas LENGLIN
- Rôle : développement, calcules physique,contrôleur  


### Sabri GHOUDANE
- Rôle : interface graphique, documentation ,contrôleur 



## Liens utiles

- [Université Cergy-Pontoise](https://mycy.cyu.fr/)
- [Ancien site](https://lachemot-lenglin.github.io/TD3/)
