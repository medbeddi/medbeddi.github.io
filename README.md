# Portfolio — Mohamed Cheikh Ahmed

Portfolio professionnel d'un ingénieur DevOps & Cloud basé à Nouakchott, Mauritanie.

**En ligne :** https://medbeddi.github.io/

## Contenu

| Section | Détail |
|---|---|
| Compétences | Stack réellement utilisée en production, par domaine |
| Parcours | Expériences professionnelles et formation, en frise chronologique |
| Projets | Plateformes en activité (Vecto, Mauriserv, Almersoul) et architectures complètes |
| Contact | Coordonnées présentées en terminal |

## Structure

```
index.html                    # Page complète, CSS et JS inclus — aucune dépendance de build
portrait.jpg                  # Photo utilisée pour les aperçus de lien (Open Graph)
CV-Mohamed-Cheikh-Ahmed.pdf   # CV téléchargeable depuis la page
.github/workflows/deploy.yml  # Publication automatique sur GitHub Pages à chaque push sur main
```

La page est un fichier unique et autonome : polices chargées depuis Google Fonts, photo intégrée
en data URI, aucune étape de build. Thèmes clair et sombre pris en charge, mise en page adaptée
jusqu'à 400 px de large.

## Développement local

```bash
npm start     # sert le dossier sur http://localhost:8000
```

## Déploiement

Tout push sur `main` déclenche le workflow GitHub Actions qui publie la racine du dépôt
sur GitHub Pages. Les configurations Netlify et Vercel sont conservées comme solutions de repli.
