# 🚀 INSTRUCTIONS ULTRA-SIMPLES

## ✅ ÉTAPE 1 : Télécharger le ZIP

Vous avez déjà téléchargé `zefix-ready.zip`

## ✅ ÉTAPE 2 : Créer le repository GitHub

1. **Allez sur** : https://github.com/new

2. **Remplissez** :
   - **Repository name** : `zefix-extractor`
   - **Description** : `Application ZEFIX pour Projexion Conseil`
   - **Public** : ✅ Coché
   - **Add a README file** : ✅ **COCHEZ** (important !)

3. **Cliquez sur** : **"Create repository"**

---

## ✅ ÉTAPE 3 : Uploader les fichiers

1. **Sur la page du nouveau repository**, cliquez sur **"Add file"** → **"Upload files"**

2. **Décompressez** `zefix-ready.zip` sur votre ordinateur

3. **Ouvrez le dossier** `zefix-ready`

4. **Sélectionnez TOUS les fichiers à l'intérieur** (Ctrl+A sur Windows / Cmd+A sur Mac) :
   ```
   ✅ api/ (dossier avec extract.py)
   ✅ index.html
   ✅ vercel.json
   ✅ requirements.txt
   ✅ README.md
   ✅ INSTRUCTIONS.md
   ```

5. **Glissez-déposez** tous ces fichiers sur la page GitHub

6. **Attendez** que toutes les barres de progression soient vertes ✅

7. **En bas**, message de commit : `Add application files`

8. **Cliquez sur** : **"Commit changes"**

---

## ✅ ÉTAPE 4 : Connecter à Vercel

1. **Allez sur** : https://vercel.com

2. **Cliquez sur** : **"New Project"**

3. **Si c'est la première fois** :
   - Cliquez sur **"Continue with GitHub"**
   - **Autorisez** Vercel à accéder à vos repositories

4. **Vous devriez voir** votre repository `zefix-extractor` dans la liste

5. **Cliquez sur** : **"Import"** (à côté de zefix-extractor)

6. **Configuration** (ne changez RIEN) :
   - Project Name : `zefix-extractor`
   - Framework Preset : Other
   - Root Directory : `./`
   - Build Command : (vide)
   - Output Directory : (vide)

7. **Cliquez sur** : **"Deploy"**

8. **Attendez 2 minutes** ⏳

---

## ✅ ÉTAPE 5 : Tester l'application

1. **Après le déploiement**, vous verrez :
   ```
   🎉 Congratulations!
   zefix-extractor Successfully Deployed
   
   🌐 https://zefix-extractor-abc123.vercel.app
   ```

2. **Cliquez sur** : **"Visit"**

3. **L'application s'ouvre** dans un nouvel onglet

4. **Cliquez sur** : **"🚀 Extraire les nouvelles entreprises"**

5. **Attendez 1-2 minutes** (extraction ZEFIX en cours)

6. **Le fichier Excel se télécharge** automatiquement 📥

7. **Ouvrez-le** → Vous avez 200-300 entreprises avec adresses complètes ! ✅

---

## 🎯 RÉCAPITULATIF

- ⏱️ **Temps total** : 5 minutes
- 🖱️ **Clics requis** : ~10
- 💻 **Code à écrire** : 0
- ✅ **Résultat** : Application fonctionnelle en ligne

---

## 🆘 EN CAS DE PROBLÈME

### **Problème 1 : "No repositories found" sur Vercel**
→ Allez sur https://github.com/settings/installations
→ Cliquez sur **Vercel** → **Configure**
→ Ajoutez `zefix-extractor` dans "Repository access"

### **Problème 2 : Erreur 404 sur l'application**
→ Vérifiez sur GitHub que tous les fichiers sont **à la racine** (pas dans un sous-dossier)
→ Le dossier `api/` doit contenir `extract.py`

### **Problème 3 : "Une erreur est survenue" lors de l'extraction**
→ Allez sur Vercel → onglet "Runtime Logs"
→ Envoyez-moi une capture des logs

---

## ✅ VOUS AVEZ RÉUSSI !

Votre application est maintenant en ligne et fonctionnelle.

**Partagez l'URL** avec votre secrétaire :
```
https://zefix-extractor-abc123.vercel.app
```

Elle pourra extraire les nouvelles entreprises chaque lundi en 1 clic ! 🎉

---

**Créé pour Projexion Conseil Sàrl**
