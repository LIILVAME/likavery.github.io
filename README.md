# Save the README.md content for GitHub repository
readme_path = Path("/mnt/data/likavery_export_final/README.md")
readme_content = """# LIKAVERY - Landing Page

Ce dépôt contient la landing page officielle du service LIKAVERY, qui facilite l’accès aux médicaments en Côte d’Ivoire via un service de livraison conforme et sécurisé.

## ✨ Fonctionnalités principales

- Présentation claire pour deux audiences : patients & pharmacies
- Animation douce d’arrière-plan
- Boutons d’action avec feedback interactif
- Intégration directe de formulaires Tally pour tests utilisateurs
- Bannière RGPD conforme à la loi ivoirienne
- Bouton WhatsApp flottant
- Message contextuel pour pharmacies (desktop uniquement)

## 🔗 Déploiement

Tu peux héberger cette page via [GitHub Pages](https://pages.github.com/) :

1. Crée un dépôt public nommé `likavery.github.io`
2. Pousse le fichier `index.html` dans la branche `main`
3. Va dans Settings > Pages > Déploiement depuis `main / (root)`
4. Accède à ta page à `https://likavery.github.io`

## 🛠 Personnalisation

Tu peux modifier le lien vers le formulaire Tally dans cette ligne :

```html
<a href="https://tally.so/r/nrqpz2" ...>Devenez partenaire</a>
