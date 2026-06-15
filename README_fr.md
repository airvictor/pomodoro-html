# Minuteur Pomodoro

Un minuteur Pomodoro minimaliste avec un magnifique affichage d'horloge numérique à sept segments, un widget météo et des durées personnalisables pour la concentration et les pauses.

![Theme](https://img.shields.io/badge/theme-light%2Fdark-cyan)
![License](https://img.shields.io/badge/license-MIT-blue)

## Fonctionnalités

- **Modes de minuteur multiples** : préréglages 60 min, 40 min (par défaut), 15 min et 5 min
- **Durée personnalisée** : ajustez la durée du minuteur directement (1-120 minutes)
- **Horloge numérique à sept segments** : horloge en temps réel au style LED classique
- **Suivi des sessions** : les points de progression indiquent les sessions de concentration terminées
- **Widget météo** : détecte automatiquement votre position et affiche la température actuelle
- **Notifications sonores** : alertes audio à la fin du minuteur (Carillon, Cloche, Numérique)
- **Thème sombre/clair** : commutation en un clic avec sauvegarde automatique des préférences
- **Paramètres persistants** : toutes les préférences sont enregistrées dans localStorage

## Utilisation

Ouvrez simplement `pomodoro.html` dans n'importe quel navigateur moderne. Aucun serveur ni étape de construction requis.

### Contrôles du minuteur

- **Démarrer/Pause** : cliquez sur le bouton principal pour démarrer ou mettre en pause
- **Réinitialiser** : cliquez sur le bouton de réinitialisation pour redémarrer la session actuelle
- **Sélection du mode** : choisissez parmi les préréglages 60m, 40m, 15m ou 5m
- **Ajustement rapide** : utilisez les boutons +/− ou saisissez directement une durée personnalisée

### Paramètres

Cliquez sur l'icône engrenage pour accéder à :
- Personnaliser la durée de chaque mode (1-120 minutes)
- Activer/désactiver le son
- Choisir le son de notification (Carillon, Cloche, Numérique)
- Basculer le mode sombre

## Comment ça fonctionne

La technique Pomodoro utilise des intervals de travail concentré (généralement 25-30 minutes) suivis de courtes pauses. Après avoir complété 4 sessions de concentration, une pause plus longue est automatiquement déclenchée.

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
- localStorage pour la persistance des paramètres
- API Open-Meteo pour les données météo

## Auteur

chatvyz

## Licence

MIT

---

*Ce README a été généré par IA*
