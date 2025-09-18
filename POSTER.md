# POSTER.md

Ce fichier contient les informations pour créer un poster LaTeX destiné à la Caravane des Quartiers.

## Objectifs du Poster

- Attirer l'attention du grand public sur les questions de vie privée numérique
- Inviter les passants à discuter avec l'équipe C4DT/gnugen
- Présenter des alternatives logicielles et services respectueux de la vie privée
- Sensibiliser de manière accessible et non-technique

## Public Cible

- Grand public français (non-académique)
- Personnes curieuses des questions de vie privée
- Utilisateurs souhaitant reprendre le contrôle de leurs données
- Visiteurs de la Caravane des Quartiers

## Contenu Suggéré

### Titre Principal
**"Reprenez le contrôle de votre vie numérique"**
*Découvrez des alternatives respectueuses de votre vie privée*

### Messages Clés Accrocheurs
- **"Êtes-vous client ou produit ?"** - Question fondamentale sur votre relation avec les services numériques
- **"Vos données valent de l'or - reprenez le contrôle !"**
- **"Des alternatives libres existent aux géants du numérique"**
- **"Protégez-vous sans sacrifier la simplicité d'usage"**
- **"Votre vie privée : un droit fondamental garanti par la Constitution suisse"** (Art. 13)

### Questions de Base pour Sensibiliser
- **Confidentialité et Vie Privée** : "Quelle est votre définition ?" - Amener les gens à réfléchir
- **Pourquoi c'est important ?** : Constitution Fédérale Suisse, Art. 13 - Protection de la vie privée
- **Chiffrement bout-à-bout** : "Les intermédiaires ne voient pas le contenu"
- **Fédération** : "Des entités indépendantes qui communiquent" (pas de monopole)

### Services/Outils Concrets à Mettre en Avant

#### 🔐 **Gestionnaires de mots de passe**
- **Bitwarden/Vaultwarden** - Synchronisation multi-appareils, gratuit, open source
- **KeePassXC** - Usage local, gratuit, multi-plateforme
- **Authentification à deux facteurs (2FA)** : Aegis (Android), OpenOTP, GNOME Authenticator

#### 🌐 **Navigateurs et Extensions**
- **Firefox** - Navigateur indépendant, open source, anti-Manifest V3
- **LibreWolf** - Firefox durci pour la confidentialité
- **Extensions essentielles** : uBlock Origin (bloque pubs/trackers), Consent-O-Matic, Cookie AutoDelete

#### 💬 **Messagerie et Réseaux Sociaux**
- **Matrix (matrix.epfl.ch)** - Messagerie chiffrée, fédérée, alternative à WhatsApp/Telegram
- **Mastodon (social.epfl.ch)** - Réseau social fédéré, alternative à Twitter/X
- **Signal** - Messagerie mobile chiffrée bout-à-bout

#### ☁️ **Stockage en Ligne**
- **Infomaniak kDrive** - Alternative suisse à Google Drive/OneDrive
- **Nextcloud** - Solution auto-hébergeable, contrôle total de vos données

#### 💻 **Bureautique et Outils**
- **LibreOffice** - Suite bureautique libre, alternative à Microsoft Office
- **OnlyOffice** - Interface similaire à MS Office, meilleure compatibilité
- **Thunderbird** - Client email libre, alternative à Outlook

#### 🎥 **Visioconférence**
- **Jitsi** - Alternative libre à Zoom
- **Element Call** - Visio intégrée à Matrix, alternative à Teams

#### 🤖 **Intelligence Artificielle**
- **Alternatives aux LLMs propriétaires** :
  - En ligne : Duck.ai, Lumo (Proton)
  - Localement : LM Studio, Ollama

### Statistiques Marquantes pour Sensibiliser
- **E-mail** : 251 millions d'emails envoyés par minute, dont 3,4 milliards de phishing quotidiens
- **Navigateurs** : Concentration du pouvoir (Chrome/Blink), impact des changements comme Manifest V3
- **Données personnelles** : Utilisées pour le profilage, ciblage publicitaire, partagées avec gouvernements

### Informations Pratiques
- **Logos** : C4DT_EPFL, gnugen et digiges bien visibles
- **Call-to-action** : "Venez discuter avec nous !" / "Posez-nous vos questions !"
- **QR codes possibles** :
  - Guide de survie gnugen : https://gnugen.ch/fr/guides/
  - Installation et ressources pratiques
- **Contact** : Linus Gasser (Centre pour la Confiance Numérique)

### Concepts Clés à Expliquer Simplement
- **Logiciel libre** : 4 libertés fondamentales (utiliser, étudier, partager, modifier)
- **Fédération vs Centralisation** : Pouvoir distribué vs contrôle unique
- **Chiffrement de transit vs bout-à-bout** : Transport sécurisé vs confidentialité totale
- **Méta-données** : "Qui, quand, où" même si le contenu est protégé
- **Modèle de menace** : "De quoi voulez-vous vous protéger ?"

## Considérations Visuelles

- Design attractif et accessible
- Utilisation de couleurs engageantes
- Police lisible à distance
- Équilibre texte/images
- Hiérarchie visuelle claire

## Librairies LaTeX Recommandées

- `tikz` pour les éléments graphiques
- `xcolor` pour la gestion des couleurs
- `graphicx` pour l'inclusion d'images/logos (C4DT_EPFL, gnugen, digiges)
- `fontspec` pour les polices (avec XeLaTeX/LuaLaTeX)
- `geometry` pour la mise en page
- `qrcode` pour les QR codes éventuels
- `multicol` pour la mise en colonnes si nécessaire
- `adjustbox` pour l'ajustement des logos