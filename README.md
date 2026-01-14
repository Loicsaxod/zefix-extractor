# 🏢 ZEFIX Extractor - Application Web

Application web pour extraire automatiquement les nouvelles entreprises depuis le registre ZEFIX (Genève et Vaud).

## ✨ Fonctionnalités

- ✅ Extraction automatique des nouvelles inscriptions (GE + VD)
- ✅ Filtrage par forme juridique (SA, Sàrl, Entreprise Individuelle)
- ✅ Export Excel avec adresses postales complètes
- ✅ Priorisation automatique (SA > Sàrl > EI)
- ✅ Interface simple et intuitive

## 🚀 Déploiement sur Vercel (1-clic)

### Prérequis
- Compte GitHub (gratuit)
- Compte Vercel (gratuit)

### Étapes

1. **Forkez ce repository**
   - Cliquez sur le bouton "Fork" en haut à droite
   - Ou créez un nouveau repository et uploadez ces fichiers

2. **Connectez Vercel à GitHub**
   - Allez sur https://vercel.com
   - Cliquez sur "Continue with GitHub"
   - Autorisez l'accès

3. **Importez le repository**
   - Sur Vercel, cliquez sur "New Project"
   - Sélectionnez ce repository
   - Cliquez sur "Import"

4. **Déployez**
   - Configuration automatique (ne changez rien)
   - Cliquez sur "Deploy"
   - Attendez 2 minutes

5. **C'est prêt !**
   - Cliquez sur "Visit" pour ouvrir l'application
   - URL : `https://votre-projet.vercel.app`

## 📦 Structure du projet

```
zefix-ready/
├── api/
│   └── extract.py          # Backend API Python
├── index.html              # Interface web
├── vercel.json             # Configuration Vercel
├── requirements.txt        # Dépendances Python
└── README.md               # Ce fichier
```

## 🔧 Utilisation

1. Ouvrez l'application web
2. Cliquez sur "🚀 Extraire les nouvelles entreprises"
3. Attendez 1-2 minutes (extraction en cours)
4. Téléchargez le fichier Excel généré

## 📊 Contenu du fichier Excel

- Priorité (Haute/Moyenne/Basse avec code couleur)
- Nom entreprise
- Forme juridique
- Canton, Ville, NPA
- **Adresse postale complète**
- Date de publication
- Colonnes vides pour enrichissement :
  - Téléphone, Email, Site web, LinkedIn
  - Statut, Notes, Date dernier contact
- Numéro RC et UID

## 🛠️ Développement local (optionnel)

### Backend (API Python)
```bash
cd api
python extract.py
```

### Frontend (Interface)
Ouvrez `index.html` dans un navigateur

## 🆘 Support

En cas de problème :
1. Vérifiez que tous les fichiers sont à la racine (pas dans un sous-dossier)
2. Vérifiez les logs sur Vercel (onglet "Runtime Logs")
3. Assurez-vous que `requirements.txt` contient bien `requests` et `openpyxl`

## 📝 Licence

Créé pour **Projexion Conseil Sàrl**
www.projexion.ch

---

**Bon prospecting ! 🚀**
