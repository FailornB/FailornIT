# Failorn IT — Site Web

Site vitrine de **Florian Beyen** — Ingénieur freelance Power Platform (Power Apps, Power Automate, SharePoint, Dataverse) basé en France.

🌐 **[failornit.com](https://failornit.com)**

---

## Structure

```
/
├── index.html          # Site complet (single-page)
├── images/             # Logos et assets
│   ├── failorn-logo.png
│   ├── power-apps.svg
│   ├── power-automate.svg
│   ├── sharepoint.svg
│   ├── dataverse.svg
│   ├── power-bi.svg
│   ├── python.svg
│   ├── react.svg
│   ├── azure.svg
│   ├── nextjs.svg
│   ├── javascript.svg
│   └── typescript.svg
├── vercel.json         # Config déploiement Vercel
└── .gitignore
```

## Stack

- HTML / CSS / JS vanilla — aucune dépendance npm
- Déploiement via **Vercel**
- Formulaire de contact via **Formspree**
- Thème jour / nuit (détection automatique système)

## Déploiement

Le site se déploie automatiquement sur Vercel à chaque `git push` sur la branche `main`.

### Configurer le formulaire de contact

1. Créer un compte sur [formspree.io](https://formspree.io)
2. Créer un formulaire avec l'adresse `f.beyen@orange.fr`
3. Copier le Form ID
4. Dans `index.html`, remplacer :
```js
const FORMSPREE_ID = 'YOUR_FORM_ID';
```

## Contact

**Florian Beyen** — f.beyen@orange.fr — [LinkedIn](https://linkedin.com/in/florian-beyen)
