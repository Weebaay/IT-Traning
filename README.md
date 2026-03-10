# 🖥️ IT Support Trainer

Application web interactive pour préparer les entretiens techniques au poste de **Technicien Support IT N1/N2**.  
Fonctionne entièrement dans le navigateur — aucun serveur, aucune dépendance.

---

## 📦 Structure du projet

```
it-trainer/
└── index.html     ← tout le projet (HTML + CSS + JS dans un seul fichier)
```

---

## 🎯 Modules disponibles

| Module | Type | Nb exercices |
|--------|------|-------------|
| ⚡ PowerShell | Terminal interactif | 8 exercices |
| 🗄️ SQL Server | Éditeur SQL simulé | 6 exercices |
| 🌐 Réseau (LAN/VLAN/WAN/Switching) | QCM explicatifs | 12 questions |
| 📋 ITIL (bases) | QCM explicatifs | 10 questions |
| 💻 VMware / Virtualisation | QCM explicatifs | 8 questions |
| 👤 Active Directory | QCM explicatifs | 6 questions |
| 📄 Cheat Sheets | Référence rapide | PS / SQL / Réseau / ITIL |

---

## 🎮 Système de progression

- **+15 XP** par exercice PowerShell réussi
- **+20 XP** par requête SQL validée
- **+10 XP** par bonne réponse QCM
- **Niveaux** : progression tous les 100 XP
- **Streak** 🔥 : compteur de bonnes réponses consécutives
- **Dashboard** : suivi visuel de la progression par module

---

## ⚡ Module PowerShell

Terminal simulé façon Windows PowerShell.  
Tu tapes une commande → validation instantanée → explication détaillée si correcte.

**Commandes couvertes :**
- `Get-Service`, `Restart-Service`
- `Get-ADUser`, `Unlock-ADAccount`
- `Get-EventLog`, `Get-ComputerInfo`
- `Test-Connection`, `Export-Csv`
- `gpupdate /force`

---

## 🗄️ Module SQL Server

Éditeur SQL avec résultat attendu affiché.  
La requête est simulée côté client (pas de vraie BDD).

**Requêtes couvertes :**
- `sys.databases`, `sys.dm_exec_sessions`, `sys.master_files`
- `SELECT`, `WHERE`, `LIKE`, `TOP`, `GROUP BY`, `ORDER BY`, `COUNT`
- Cas support réels : audit, espaces disque, recherche utilisateurs

---

## 🌐 Module Réseau

QCM avec explication complète après chaque réponse.

**Thèmes :**
- LAN / WAN / WLAN
- VLAN, ports access vs trunk, 802.1Q
- DHCP, APIPA (169.254.x.x)
- Modèle OSI (couches 2 et 3)
- Diagnostic : `ipconfig`, `ping`, `tracert`, `nslookup`
- Adressage privé RFC 1918

---

## 📋 Module ITIL

**Thèmes :**
- Incident vs Problème vs Changement
- SLA, OLA, CMDB, CAB
- Priorités P1→P4 (impact × urgence)
- Escalades fonctionnelle et hiérarchique
- Workaround (solution de contournement)
- EasyVista et outils ITSM
- ITIL 4 — Service Value Chain

---

## 💻 Module VMware / Virtualisation

**Thèmes :**
- Snapshots, vMotion, Datastores
- Hyperviseur type 1 vs type 2
- VM vs Conteneur
- Support Citrix côté utilisateur
- VMware Horizon — dépannage accès bureau virtuel

---

## 👤 Module Active Directory

**Thèmes :**
- Compte verrouillé vs désactivé
- `Unlock-ADAccount`, `Enable-ADAccount`
- GPO (Group Policy Object)
- OU (Organizational Unit)
- Droits NTFS et permissions de partage
- Contrôleur de domaine (DC)

---

## 📄 Cheat Sheets

Référence rapide consultable à tout moment :

- **PowerShell** : services, AD, réseau, événements, fichiers, filtres
- **SQL** : SELECT, WHERE, JOIN, GROUP BY, vues système SQL Server
- **Réseau** : commandes diagnostic, plages IP privées, modèle OSI, VLAN
- **ITIL** : cycle incident, priorités, types de changements, terminologie

---

## 🛠️ Technique

- **Aucune dépendance** — HTML/CSS/JS vanilla pur
- **Aucun backend** — tout tourne dans le navigateur
- **Single file** — un seul fichier `index.html` auto-suffisant
- **Responsive** — fonctionne sur desktop, tablette, mobile
- Polices Google Fonts : `Space Mono` + `Syne`

---

## 📝 Offre d'emploi cible

Ce projet couvre l'ensemble des compétences requises pour le poste :

| Compétence offre | Module |
|-----------------|--------|
| Support N1/N2, ITIL, EasyVista | 📋 ITIL |
| PowerShell / Scripting | ⚡ PowerShell |
| SQL Server (consultation simple) | 🗄️ SQL |
| LAN / VLAN / WLAN / Switching / Routing | 🌐 Réseau |
| VMware / Citrix (côté utilisateur) | 💻 VMware |
| Active Directory (gestion utilisateurs) | 👤 Active Directory |

---
