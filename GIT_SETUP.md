# Configuration Git pour le projet Tabac Montmeyan

## Lier avec GitHub

### 1. Créer un repository sur GitHub
- Allez sur https://github.com
- Cliquez sur "New repository"
- Nommez-le "tabac-montmeyan"
- Ne cochez PAS "Initialize with README" (nous en avons déjà un)
- Cliquez sur "Create repository"

### 2. Lier le repository local avec GitHub
```bash
git remote add origin https://github.com/VOTRE_USERNAME/tabac-montmeyan.git
git push -u origin main
```

### 3. Vérifier la connexion
```bash
git remote -v
```

## Commandes utiles

### Sauvegarder vos modifications
```bash
git add .
git commit -m "Description de vos modifications"
git push
```

### Récupérer les dernières modifications
```bash
git pull
```
