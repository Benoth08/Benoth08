# Instructions de mise en place du Profile GitHub

Ce repo doit être mis sur GitHub avec un **nom identique à ton
username GitHub**. C'est ce qui permet à GitHub d'afficher
automatiquement le `README.md` en haut de ta page profil.

## Si ton username GitHub est `mikafere`

```bash
cd /tmp
mkdir mikafere
cd mikafere

# Copier les deux README depuis le dossier extrait
cp <chemin-vers-mikafere-profile>/README.md .
cp <chemin-vers-mikafere-profile>/README.fr.md .

git init
git add README.md README.fr.md
git commit -m "Profile README — bilingual EN/FR"
git branch -M main
git remote add origin https://github.com/mikafere/mikafere.git
git push -u origin main
```

⚠️ **Le repo GitHub doit s'appeler exactement comme ton username.**
Si tu t'appelles `mikafere` sur GitHub, le repo doit s'appeler
`mikafere`. Si tu t'appelles `michael-fere`, le repo doit s'appeler
`michael-fere`.

## Liens à mettre à jour avant de pusher

Dans `README.md` et `README.fr.md`, remplacer :
- `<user>` → ton vrai username GitHub
- L'URL LinkedIn — vérifie qu'elle est correcte
  (actuellement `michael-fere-data-scientist`)

## Vérification

Une fois pushé, va sur `https://github.com/<ton-username>` (sans
le `/repo`) — tu dois voir ton README s'afficher en haut.

## Mises à jour futures

- **Ajout d'un projet** → édite `README.md` et `README.fr.md`, garde
  la même structure.
- **Changement de poste** → mets à jour la section "Open to" / "Disponible pour"
  + ajoute la nouvelle expérience en haut.
- **Nouvelle certification** → ajoute dans "Selected Certifications".

## Convention markdown que j'ai utilisée

- Liens GitHub absolus (`https://github.com/...`) pour qu'ils marchent
  partout (pas juste sur le repo).
- Badges shields.io statiques (pas de service tiers → pas de risque
  de cassure).
- Bilingue avec un badge en haut de chaque README qui pointe vers
  l'autre langue (`[FR Version]` et `[EN Version]`).
- Pas de mention de prétentions salariales — comme demandé.
