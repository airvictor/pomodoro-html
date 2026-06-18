# Minuteur Pomodoro

Un minuteur Pomodoro minimaliste avec un magnifique affichage d'horloge numérique à sept segments, un widget météo et des durées personnalisables pour la concentration et les pauses.

[English](README.md) · [Français](README_fr.md) · [中文](README_zh-CN.md)

![Theme](https://img.shields.io/badge/theme-light%2Fdark-cyan)
![License](https://img.shields.io/badge/license-MIT-blue)

## Fonctionnalités

- **Modes de minuteur multiples** : préréglages 60 min, 40 min (par défaut), 15 min et 5 min (tous personnalisables)
- **Durée personnalisée** : ajustez la durée du minuteur directement (minimum 1 minute, sans maximum)
- **Horloge numérique à sept segments** : horloge en temps réel au style LED classique avec affichage de la date
- **Suivi des sessions** : les points de progression indiquent les sessions de concentration terminées
- **Widget météo** : détecte automatiquement votre position et affiche la température actuelle
- **Notifications sonores** : alertes audio à la fin du minuteur (Carillon, Cloche, Numérique)
- **Thème sombre/clair** : commutation en un clic
- **Garder éveillé** : empêcher l'écran de s'éteindre pendant le minuteur
- **Verrouillage de l'interface** : verrouiller l'interface pour éviter les clics accidentels
- **Réinitialisation de session** : tous les paramètres sont réinitialisés au rafraîchissement de la page

## Utilisation

Ouvrez simplement `index.html` dans n'importe quel navigateur moderne. Aucun serveur ni étape de construction requis.

### Contrôles du minuteur

- **Démarrer/Pause** : cliquez sur le bouton principal pour démarrer ou mettre en pause
- **Réinitialiser** : cliquez sur le bouton de réinitialisation pour redémarrer la session actuelle
- **Verrouiller** : cliquez sur le bouton de verrouillage pour éviter les interactions accidentelles
- **Sélection du mode** : choisissez parmi les préréglages 60m, 40m, 15m ou 5m
- **Ajustement rapide** : utilisez les boutons +/− ou saisissez directement une durée personnalisée

### Paramètres

Cliquez sur l'icône engrenage pour accéder à :
- Personnaliser la durée de chaque mode (sans limite maximale)
- Activer/désactiver le son
- Choisir le son de notification (Carillon, Cloche, Numérique)
- Activer/désactiver Garder éveillé (empêcher l'écran de s'éteindre)
- Basculer le mode sombre

## Comment ça fonctionne

La technique Pomodoro utilise des intervalles de travail concentré (généralement 25-30 minutes) suivis de courtes pauses. Après avoir complété 4 sessions de concentration, une pause plus longue est automatiquement déclenchée.

```
Session de concentration → Pause courte → Session de concentration → Pause courte → Session de concentration → Pause courte → Session de concentration → Pause longue
```

## Compatibilité des navigateurs

Fonctionne mieux avec les navigateurs modernes supportant ES6+ :
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## Stack technique

- HTML, CSS, JavaScript pur (sans dépendances)
- API Web Audio pour la génération des sons
- API Wake Lock pour empêcher la mise en veille de l'écran
- API Open-Meteo pour les données météo

## Auteur

astrovyz

## Licence

MIT

---

*Ce README a été généré par IA*
