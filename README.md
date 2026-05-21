# Site Valérie Vie – Psychanalyse à Uzès

## Contenu du site
5 pages HTML complètes, prêtes à l'emploi :
- `index.html` — Accueil
- `seminaires.html` — Séminaires
- `atelier-lectures.html` — Atelier Lectures
- `cartel.html` — Cartel
- `contact.html` — Contact
- `style.css` — Feuille de style (partagée)
- `nav.js` — Navigation mobile (burger menu)

## Déploiement gratuit sur GitHub Pages

### Étape 1 – Créer un compte GitHub
Aller sur https://github.com et créer un compte gratuit.

### Étape 2 – Créer un dépôt
1. Cliquer sur "New repository"
2. Nommer le dépôt : `valerievie-psychanalyse` (ou ce que vous voulez)
3. Le rendre **Public**
4. Cliquer "Create repository"

### Étape 3 – Uploader les fichiers
1. Cliquer "uploading an existing file"
2. Glisser-déposer TOUS les fichiers de ce dossier
3. Cliquer "Commit changes"

### Étape 4 – Activer GitHub Pages
1. Aller dans Settings > Pages
2. Source : "Deploy from a branch"
3. Branch : `main` / `root`
4. Cliquer Save

Le site sera accessible à : `https://votre-pseudo.github.io/valerievie-psychanalyse/`

---

## Ajouter un nom de domaine personnalisé (~8 €/an)

1. Acheter un domaine `.fr` sur OVH, Infomaniak ou Namecheap
   Ex : `valerievie-psychanalyse.fr`

2. Dans GitHub Pages > Settings > Pages > Custom domain
   Saisir votre domaine et cliquer Save

3. Chez votre registrar, ajouter ces enregistrements DNS :
   ```
   A     @    185.199.108.153
   A     @    185.199.109.153
   A     @    185.199.110.153
   A     @    185.199.111.153
   CNAME www  votre-pseudo.github.io
   ```

4. Cocher "Enforce HTTPS" dans GitHub Pages

**Résultat : site sécurisé HTTPS sur votre propre domaine pour ~8 €/an.**

---

## Mettre à jour le contenu

Pour modifier une page :
1. Aller sur votre dépôt GitHub
2. Cliquer sur le fichier à modifier (ex: `seminaires.html`)
3. Cliquer l'icône crayon (Edit)
4. Modifier le texte
5. Cliquer "Commit changes"

Le site se met à jour automatiquement en 1–2 minutes.

---

## SEO – Checklist

- [ ] Inscrire le site sur Google Search Console (gratuit)
- [ ] Créer une fiche Google Business Profile (gratuit)
- [ ] Vérifier que les balises `<meta name="description">` sont bien remplies (déjà fait)
- [ ] Ajouter un sitemap.xml (optionnel mais utile)

## Coût total

| Poste | Coût |
|-------|------|
| Hébergement GitHub Pages | 0 € |
| Nom de domaine .fr | ~8 €/an |
| **Total** | **~8 €/an** |

vs. Wix : ~150–200 €/an
