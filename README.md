# 🖥️ Jonathan PC Service — Site Web

Site vitrine pour Jonathan PC Service, réparation informatique à domicile à Guéret (23).

## 📁 Structure du projet

```
jonathan-pc-service/
├── index.html          ← Le site complet (1 seul fichier)
├── public/
│   └── logo.png        ← Ton logo
├── vercel.json         ← Configuration Vercel
├── package.json        ← Infos du projet
└── README.md           ← Ce fichier
```

## 🚀 Comment déployer sur Vercel via GitHub

### Étape 1 : Créer un compte GitHub (si pas déjà fait)
1. Va sur **https://github.com** et crée un compte
2. Confirme ton email

### Étape 2 : Créer un nouveau repository
1. Clique sur le **+** en haut à droite → **New repository**
2. Nom : `jonathan-pc-service`
3. Laisse en **Public**
4. Clique **Create repository**

### Étape 3 : Uploader les fichiers
1. Sur la page du repo, clique **uploading an existing file**
2. Glisse tous les fichiers du dossier :
   - `index.html`
   - `vercel.json`
   - `package.json`
   - Le dossier `public/` avec `logo.png` dedans
3. Clique **Commit changes**

### Étape 4 : Connecter à Vercel
1. Va sur **https://vercel.com** et connecte-toi avec ton compte GitHub
2. Clique **Add New → Project**
3. Sélectionne ton repo `jonathan-pc-service`
4. Dans les settings :
   - **Framework Preset** : Other
   - **Output Directory** : `.` (un point)
5. Clique **Deploy**

### Étape 5 : C'est en ligne ! 🎉
Vercel te donne une URL du type `jonathan-pc-service.vercel.app`

### (Optionnel) Nom de domaine personnalisé
Tu peux acheter un domaine (ex: `jonathanpcservice.fr`) sur OVH ou Ionos (~5-10€/an) et le connecter dans les settings de Vercel → Domains.

## ✏️ Modifier le site
- Le SIRET est marqué "en cours d'attribution" — pense à le mettre à jour quand tu le recevras
- Tu peux modifier les horaires, prix ou textes directement dans `index.html`
- Pour modifier, va sur GitHub → clique sur le fichier → icône crayon → modifie → Commit
- Vercel redéploie automatiquement à chaque modification sur GitHub

## 📞 Contact
Jonathan PC Service
📧 jopcservice@gmail.com
📞 06 41 99 56 70
