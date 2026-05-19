# AGORA Chaussures — Catalogue

## 📁 Fichiers dans ce dossier

| Fichier | Rôle |
|---|---|
| `dashboard.html` | Ton outil d'administration (ouvre sur ton laptop) |
| `index.html` | Le catalogue public (visible sur Netlify) |
| `catalogue.json` | Les données des produits |
| `logo-agora.jpg` | Le logo |

---

## 🚀 Démarrage rapide (5 minutes)

### Étape 1 — Ajouter des produits

1. Ouvre `dashboard.html` dans ton navigateur (double-clic)
2. Ajoute tes produits :
   - Va sur **imgbb.com** → upload ta photo → copie le **"Direct link"**
   - Colle l'URL dans le champ image du dashboard
   - Remplis les infos et clique **"Enregistrer"**
3. Clique **"Exporter catalogue.json"** → ça télécharge le fichier

### Étape 2 — Mettre à jour le fichier JSON

Remplace le fichier `catalogue.json` de ce dossier par le fichier téléchargé.

### Étape 3 — Déployer sur Netlify

**Première fois :**
1. Va sur [netlify.com](https://netlify.com) → créer un compte gratuit
2. Clique **"Add new site"** → **"Deploy manually"**
3. Glisse-dépose **tout ce dossier** sur Netlify
4. Ton site est en ligne ! Tu reçois une URL ex: `agora-abc123.netlify.app`

**Mises à jour suivantes :**
1. Exporte le nouveau `catalogue.json` depuis le dashboard
2. Sur Netlify → ton site → **"Deploys"** → glisse le dossier mis à jour
3. Site mis à jour en 30 secondes ✅

---

## 💡 Workflow quotidien

```
Dashboard (laptop) → Exporter JSON → Glisser sur Netlify → Site mis à jour
```

Temps total : **moins de 2 minutes** par mise à jour.

---

## 🌍 Langues

Le catalogue public supporte automatiquement :
- 🇫🇷 Français
- 🇸🇦 Arabe
- 🇬🇧 Anglais

Le visiteur peut switcher en haut à droite.

## 📂 Catégories

- **Homme** / Man / رجال
- **Femme** / Woman / نساء  
- **Enfant** / Child / أطفال
  - Garçon / Boy
  - Fille / Girl
