![image](https://github.com/user-attachments/assets/4031a91b-5301-48ee-a5d1-3ad3461f44c1)

# 📲 Installer SideStore sur iPhone depuis Windows

> Un guide simple et à jour pour installer SideStore sans Mac, directement depuis Windows.  
> ⚠️ Compatible iOS **17.0 à 18.5** – **non encore testé sur iOS 18.6** (mise à jour à venir)

![Plateforme](https://img.shields.io/badge/plateforme-Windows-blue)
![iOS](https://img.shields.io/badge/iOS-17.0--18.5-green)
![Méthode-sans%20Mac-important](https://img.shields.io/badge/m%C3%A9thode-sans%20Mac-important)
![SideStore](https://img.shields.io/github/stars/SideStore/SideStore?style=social)

---

## 🧰 Prérequis

- ✅ iPhone sous iOS 17.0 à 18.5
- ⚠️ iOS 18.6 **non encore testé** — mise à jour du guide prévue dès confirmation
- ✅ Un PC sous Windows 10 ou 11
- ✅ Un identifiant Apple (peut être temporaire)
- ✅ Un câble USB pour connecter l’iPhone
- ✅ iTunes + iCloud installés (**depuis le site Apple**, pas le Microsoft Store)

---

## 1️⃣ Installer iTunes & iCloud (depuis le site Apple)

**⚠️ Important : n'utilise pas les versions du Microsoft Store, elles causent des bugs de détection.**

- 🔗 [Télécharger iTunes](https://www.apple.com/itunes/download/)
- 🔗 [Télécharger iCloud](https://support.apple.com/fr-fr/HT204283)

👉 Une fois installés, redémarre ton PC.

---

## 2️⃣ Télécharger et installer SideStore (Windows)

1. Va sur le site officiel :  
   🔗 [https://sidestore.io](https://sidestore.io)

2. Clique sur **“Download”** et choisis la version **Windows**.

3. Décompresse le fichier `.zip` téléchargé.

4. Lance l’application `SideStore.exe`.

5. Connecte ton iPhone en USB.

6. Suis les instructions affichées pour :

   - Lier ton identifiant Apple
   - Générer le profil de provisioning
   - Installer SideStore sur ton iPhone

---

## 3️⃣ Faire confiance au certificat

Sur ton iPhone :

1. Va dans **Réglages > Général > VPN et gestion de l’appareil**.

2. Sélectionne ton adresse email dans la section "Développeur" et clique sur **Faire confiance**.

---

## 4️⃣ Activer la synchronisation Wi-Fi (optionnel mais recommandé)

> Pour permettre à SideStore de re-signer automatiquement tes apps sans câble.

1. Ouvre **iTunes** sur ton PC.
2. Clique sur l’icône de ton iPhone.
3. Coche **“Synchroniser avec cet iPhone en Wi-Fi”** et clique sur "Appliquer".

---

## 5️⃣ Installer des fichiers .ipa avec SideStore

1. Télécharge un fichier `.ipa` (ex: AltStore, DolphiniOS, UTM…).
2. Ouvre **SideStore** sur ton iPhone.
3. Va dans l’onglet **My Apps** puis appuie sur le **+**.
4. Sélectionne ton fichier `.ipa`, l’installation démarre.

---

## 🔄 Renouvellement automatique (chaque 7 jours)

Les apps expirent tous les **7 jours** avec un compte Apple gratuit.  
SideStore peut les re-signer automatiquement si :

- ✅ L’option Wi-Fi Sync est activée dans iTunes
- ✅ Ton PC est allumé et SideStore fonctionne en arrière-plan

---

## 🛠️ Dépannage rapide

| Problème                            | Solution                                                                 |
|-------------------------------------|--------------------------------------------------------------------------|
| App SideStore qui crash             | Redémarre le PC, reconnecte l’iPhone, et relance SideStore              |
| L’app ne s’installe pas             | Vérifie que le certificat est bien “fait confiance” dans les réglages   |
| Erreur Apple ID / provision         | Change de compte Apple ou révoque les anciens profils                   |

---

## 📡 Ressources utiles

- 🌐 Site officiel : [https://sidestore.io](https://sidestore.io)
- 💬 Discord communautaire : [https://discord.gg/RgpFBX3Q3k](https://discord.gg/RgpFBX3Q3k)
- 🧑‍💻 GitHub officiel : [https://github.com/SideStore/SideStore](https://github.com/SideStore/SideStore)


---

## ⭐️ Un petit mot

Ce guide a été rédigé pour aider ceux qui souhaitent utiliser SideStore depuis Windows, **sans avoir besoin d’un Mac ou d’un jailbreak**.  
N’hésitez pas à laisser une ⭐️ si ce guide vous a aidé, ou à proposer des améliorations via une pull request 🙌
