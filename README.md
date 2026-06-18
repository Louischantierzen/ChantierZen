# 🏗️ ChantierZen — Guide de mise en ligne

## Structure du projet
```
chantierzen/
├── index.html          → Page d'accueil
├── connexion.html      → Inscription / Connexion
├── recherche.html      → Recherche artisans
├── profil.html         → Profil public artisan
├── gestion.html        → Service gestion de chantier
├── dashboard.html      → Tableau de bord artisan
├── messagerie.html     → Messagerie
├── admin.html          → Tableau de bord Admin
└── vercel.json         → Configuration Vercel
```

---

## 🚀 Mise en ligne sur Vercel (gratuit)

### Étape 1 — Créer un compte GitHub
1. Va sur **github.com**
2. Clique **"Sign up"**
3. Crée ton compte gratuit

### Étape 2 — Créer un nouveau dépôt
1. Clique le **"+"** en haut à droite
2. **"New repository"**
3. Nom : **chantierzen**
4. Coche **"Public"**
5. Clique **"Create repository"**

### Étape 3 — Uploader les fichiers
1. Dans ton dépôt, clique **"uploading an existing file"**
2. Glisse-dépose **tous les fichiers** de ce dossier
3. Clique **"Commit changes"**

### Étape 4 — Déployer sur Vercel
1. Va sur **vercel.com**
2. Clique **"Sign up"** → connecte avec GitHub
3. Clique **"Add New Project"**
4. Sélectionne ton dépôt **chantierzen**
5. Clique **"Deploy"**
6. ✅ Ton site est en ligne en 2 minutes !

### Étape 5 — Ton domaine chantierzen.be
1. Achète **chantierzen.be** sur combell.com (~15€/an)
2. Dans Vercel → ton projet → **"Domains"**
3. Ajoute **chantierzen.be**
4. Suis les instructions DNS de Vercel
5. ✅ Ton domaine est connecté !

---

## 💰 Coûts
| Service | Coût |
|---|---|
| Vercel (hébergement) | **Gratuit** |
| GitHub | **Gratuit** |
| chantierzen.be | **~15€/an** |
| **Total** | **~15€/an** |

---

## 📧 Connecter le formulaire de contact
Pour recevoir les demandes de gestion de chantier par email :
1. Crée un compte sur **formspree.io** (gratuit)
2. Remplace `ACTION_URL` dans gestion.html par ton URL Formspree
3. Tu recevras chaque demande directement dans ta boîte mail

---

## 🗄️ Prochaine étape — Base de données
Quand tu veux rendre la plateforme interactive (vrais profils artisans, messagerie réelle...) :
- **Supabase** (gratuit) → supabase.com
- On code ensemble la connexion

---

## 📞 Support
Ce projet a été construit avec Claude — continue à travailler avec lui pour les évolutions !
