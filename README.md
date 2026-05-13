# mathequete-privacy

Politique de confidentialité publique de l'application **Mathéquête** (Google Play Store, `com.coresrdi.mathequete`), hébergée via GitHub Pages.

## URLs publiques

- 🇫🇷 **Français (principale)** : https://coresrdi.github.io/mathequete-privacy/
- 🇬🇧 **English** : https://coresrdi.github.io/mathequete-privacy/en/

Ces URLs doivent être collées dans :

1. **Google Play Console** → *Croissance > Présence sur le Store > Fiche du Store principal* → champ "Politique de confidentialité"
2. **Google Play Console** → *Politique > Contenu de l'app* → section "Politique de confidentialité"
3. **À l'intérieur de l'app** (futur) → écran *Paramètres > À propos > Politique de confidentialité*

## Structure du repo

```
.
├── index.html        # Version française (canonique)
├── en/
│   └── index.html    # Version anglaise
└── README.md
```

## Mettre à jour la politique

1. Modifier `index.html` (et `en/index.html` si changement de fond).
2. Mettre à jour la ligne **"Dernière mise à jour"** en haut du document.
3. Commit + push sur `main` :
   ```bash
   git add .
   git commit -m "docs(privacy): description du changement"
   git push origin main
   ```
4. GitHub Pages redéploie automatiquement en ~1 minute.

## Activation de GitHub Pages (une seule fois)

Après création du repo :

1. Sur GitHub → *Settings* → *Pages*
2. **Source** : `Deploy from a branch`
3. **Branch** : `main` / dossier `/ (root)`
4. **Save**
5. Attendre 1-2 min, l'URL devient active.

## Historique des modifications

Toutes les versions précédentes sont consultables via `git log` ou l'onglet *Commits* sur GitHub. C'est un avantage important en cas d'audit légal (RGPD, COPPA, Loi 25).

## Licence

© 2026 Jeff Gravel — coresrdi. Le contenu de cette politique est publié uniquement à titre informatif et ne constitue pas un modèle libre de droits.
