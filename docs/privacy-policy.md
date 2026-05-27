# Politique de Confidentialité — She Want Me

**Version :** 1.0  
**Date d'entrée en vigueur :** 27 mai 2025  
**Dernière mise à jour :** 27 mai 2025

---

> **Note :** Ce document a été révisé juridiquement. Toute modification substantielle des pratiques de traitement de données devra faire l'objet d'une mise à jour de cette politique.

---

## Résumé rapide

| Élément                       | Détail                                                         |
| ----------------------------- | -------------------------------------------------------------- |
| **Application**               | She Want Me — chat vidéo aléatoire 1:1                         |
| **Responsable de traitement** | Jean de Dieu SESSOU (auto-entrepreneur)                        |
| **Contact privacy**           | sessoujeandedieu@gmail.com                                     |
| **Données collectées**        | Pseudo, genre, pays, bio, photo de profil, identifiant anonyme |
| **Données NON collectées**    | Email, téléphone, localisation GPS, données bancaires          |
| **Appels vidéo**              | Transmis en direct via Agora.io — non enregistrés              |
| **Âge minimum**               | 18 ans                                                         |
| **Marchés principaux**        | Afrique de l'Ouest (UEMOA)                                     |
| **Durée de rétention**        | Jusqu'à suppression du compte ou désinstallation               |

---

## Politique de Confidentialité complète

### 1. Qui sommes-nous ?

She Want Me est une application mobile de chat vidéo aléatoire 1:1 destinée à la diaspora ouest-africaine. Elle permet à des utilisateurs de se connecter de façon spontanée et anonyme, sans créer de compte traditionnel.

**Responsable de traitement des données :**

Jean de Dieu SESSOU  
Auto-entrepreneur  
17 rue Kouenou, Lomé, Togo  
Email : sessoujeandedieu@gmail.com

---

### 2. Données que nous collectons

#### 2.1 Données fournies par l'utilisateur

Lors de la création de votre profil, vous fournissez volontairement :

- **Pseudo** (surnom) : maximum 20 caractères. Aucun nom réel n'est requis.
- **Genre** : femme ou homme (utilisé pour les préférences de matching).
- **Pays** : sélectionné dans une liste — non une localisation GPS précise.
- **Bio** (optionnel) : texte libre, maximum 160 caractères.
- **Photo de profil** (optionnel) : image uploadée depuis votre appareil.

> Nous ne collectons **jamais** votre email, numéro de téléphone, nom réel, adresse, ou données bancaires.

#### 2.2 Données générées automatiquement

- **Identifiant anonyme (UID)** : un identifiant technique unique généré par Firebase Authentication lors de votre première utilisation. Il n'est pas lié à votre identité réelle (pas d'email, pas de téléphone).
- **Données de présence** : un signal de connexion/déconnexion (timestamp) indiquant que vous êtes en ligne, sans stocker votre adresse IP ou localisation.
- **Données de session** : lors d'un appel, nous enregistrons l'identifiant de session, les UIDs des deux participants, le nom du canal Agora et le statut de la session (actif/terminé/skippé).
- **Compteur de recherches** : un compteur journalier local (stocké uniquement sur votre appareil) pour gérer la limite quotidienne de recherches.
- **Confirmation d'âge** : un marqueur local (sur votre appareil) indiquant que vous avez confirmé avoir 18 ans ou plus.

#### 2.3 Données collectées par nos prestataires

**Firebase (Google LLC)**

- Héberge notre base de données en temps réel et notre système d'authentification anonyme.
- Google peut collecter des données de diagnostic et de performance dans le cadre des services Firebase.
- Politique de confidentialité : [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

**Agora.io**

- Transmet les flux vidéo et audio en temps réel pendant vos appels.
- Les flux ne sont **pas enregistrés** par She Want Me. Agora peut collecter des métadonnées techniques (qualité de réseau, type d'appareil) pour le bon fonctionnement du service.
- Politique de confidentialité : [https://www.agora.io/en/privacy-policy/](https://www.agora.io/en/privacy-policy/)

**Cloudinary**

- Héberge vos photos de profil si vous en téléversez une.
- Les photos sont associées à votre UID anonyme, non à votre identité réelle.
- Politique de confidentialité : [https://cloudinary.com/privacy](https://cloudinary.com/privacy)

**RevenueCat**

- Gère vos abonnements Premium.
- Votre UID anonyme est transmis à RevenueCat pour lier votre abonnement à votre session.
- Les données de paiement (carte, facturation) sont exclusivement traitées par l'App Store d'Apple ou le Google Play Store — She Want Me n'y a jamais accès.
- Politique de confidentialité : [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)

**Apple App Store / Google Play Store**

- Traitent les paiements des abonnements Premium.
- Politiques respectives : [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) et [policies.google.com/privacy](https://policies.google.com/privacy)

---

### 3. Comment nous utilisons vos données

| Finalité                                                       | Données utilisées                            | Base légale                      |
| -------------------------------------------------------------- | -------------------------------------------- | -------------------------------- |
| Vous connecter de façon anonyme                                | UID Firebase                                 | Exécution du service             |
| Afficher votre profil aux autres utilisateurs pendant un match | Pseudo, genre, pays, bio, photo              | Exécution du service             |
| Vous mettre en relation avec un autre utilisateur compatible   | UID, genre, filtre de pays                   | Exécution du service             |
| Gérer et établir les appels vidéo                              | UID, canal Agora, données de session         | Exécution du service             |
| Afficher le compteur d'utilisateurs en ligne                   | Données de présence agrégées                 | Intérêt légitime                 |
| Gérer votre abonnement Premium                                 | UID, statut d'abonnement RevenueCat          | Exécution du contrat             |
| Héberger votre photo de profil                                 | Photo, UID                                   | Consentement (action volontaire) |
| Limiter les abus (quota journalier)                            | Compteur local sur l'appareil                | Intérêt légitime                 |
| Traiter les signalements d'utilisateurs                        | UID du signalant, UID signalé, ID de session | Intérêt légitime (sécurité)      |

Nous n'utilisons **jamais** vos données à des fins publicitaires ou de marketing tiers, et nous ne **vendons jamais** vos données à des tiers.

---

### 4. Partage des données

Nous ne partageons vos données qu'avec les prestataires techniques listés à la section 2.3, uniquement dans le cadre nécessaire au fonctionnement du service.

Nous pouvons également divulguer vos données si :

- La loi l'exige (réquisition judiciaire, demande d'autorité compétente).
- Cela est nécessaire pour protéger les droits, la sécurité ou les biens de She Want Me ou de tiers.

> Si l'app devient accessible depuis des pays de l'UE, un Data Processing Agreement (DPA) devra être signé avec chaque prestataire traitant des données de résidents européens.

---

### 5. Transferts internationaux de données

Vos données sont hébergées et traitées sur des serveurs opérés par Google (Firebase), Agora.io et Cloudinary, qui peuvent être situés hors d'Afrique de l'Ouest (notamment aux États-Unis et en Europe).

> Les lois sur la protection des données d'Afrique de l'Ouest (notamment le Sénégal — loi n°2008-12, la Côte d'Ivoire — loi n°2013-450, le Togo — loi n°2019-014) encadrent les transferts de données hors du territoire. Ces transferts reposent sur le consentement de l'utilisateur lors de l'utilisation des services, et sur les clauses contractuelles des prestataires (Firebase, Agora, Cloudinary).

---

### 6. Durée de conservation

| Données                                  | Durée de conservation                                         |
| ---------------------------------------- | ------------------------------------------------------------- |
| Profil (pseudo, genre, pays, bio, photo) | Jusqu'à suppression du profil ou désinstallation de l'app     |
| UID anonyme Firebase                     | Jusqu'à suppression de l'app / réinitialisation de l'appareil |
| Données de session (calls)               | [À DÉFINIR — ⚠️ recommandé : 90 jours maximum]                |
| Présence (online/offline)                | Supprimée automatiquement à la déconnexion                    |
| Signalements                             | [À DÉFINIR avant la mise en production d'Epic 2]              |
| Données de paiement RevenueCat           | Selon la politique de RevenueCat et des stores                |
| Données locales (AsyncStorage)           | Jusqu'à désinstallation de l'app                              |

> **Note développeur :** Les durées marquées [À DÉFINIR] doivent être décidées avant la mise en production des features correspondantes et cette politique mise à jour en conséquence.

---

### 7. Vos droits

Conformément aux lois applicables sur la protection des données (notamment la loi sénégalaise n°2008-12, la loi ivoirienne n°2013-450 et les réglementations similaires dans les pays UEMOA), vous disposez des droits suivants :

- **Droit d'accès** : Obtenir une copie des données que nous détenons sur vous.
- **Droit de rectification** : Corriger des données inexactes (via l'écran Profil de l'app).
- **Droit à l'effacement** : Demander la suppression de vos données.
- **Droit à la limitation** : Demander la restriction du traitement de vos données.
- **Droit à la portabilité** : Recevoir vos données dans un format structuré.
- **Droit d'opposition** : Vous opposer à certains traitements basés sur l'intérêt légitime.

Pour exercer ces droits, contactez-nous à : **privacy@she-want-me.app**

Nous nous engageons à répondre dans un délai de **30 jours**.

> **Note :** Du fait de l'authentification anonyme, il n'est pas possible de vous identifier par email ou téléphone. Pour exercer vos droits, vous devrez fournir votre UID Firebase (accessible dans les paramètres de l'app — [à implémenter]) ou tout autre moyen permettant de vous identifier.

---

### 8. Sécurité des données

Nous mettons en place des mesures techniques pour protéger vos données :

- **Chiffrement en transit** : Toutes les communications entre l'app et nos serveurs utilisent HTTPS/TLS.
- **Authentification anonyme** : Aucune donnée d'identité réelle (email, téléphone) n'est collectée ni stockée.
- **Accès restreint** : Seul le responsable de traitement a accès à la base de données Firebase.
- **Isolation des sessions** : Les données d'un appel ne sont accessibles qu'aux deux participants concernés.
- **Photos** : Les photos de profil sont stockées avec un identifiant anonyme sur Cloudinary.

Aucun système n'est infaillible. En cas d'incident de sécurité affectant vos données, nous nous engageons à vous en informer dans les délais prévus par la loi applicable.

---

### 9. Enfants et mineurs

She Want Me est une application **réservée aux personnes âgées de 18 ans et plus**. Un écran de confirmation d'âge est présenté à chaque nouvel utilisateur.

Nous ne collectons pas sciemment de données personnelles de personnes mineures. Si vous avez connaissance qu'un mineur utilise l'application, contactez-nous à **privacy@she-want-me.app** pour que nous prenions les mesures nécessaires.

> **Note :** La confirmation d'âge actuelle repose sur une déclaration sur l'honneur (case à cocher), sans vérification d'identité. Selon l'évolution réglementaire, une vérification plus stricte pourrait être requise.

---

### 10. Cookies et suivi

She Want Me est une **application mobile native** — elle n'utilise pas de cookies au sens traditionnel du terme (cookies de navigateur web).

Des technologies similaires de stockage local (AsyncStorage) sont utilisées uniquement pour :

- Mémoriser votre confirmation d'âge
- Mémoriser que votre profil est complété
- Gérer votre quota journalier de recherches

Ces données restent sur votre appareil et ne sont pas transmises à des tiers.

---

### 11. Modifications de cette politique

En cas de modification importante de cette politique, nous vous en informerons :

- Par une notification dans l'application, ou
- Par une mise à jour visible lors du prochain lancement de l'app.

La date de "Dernière mise à jour" en haut de ce document indique la version en vigueur. La version précédente reste consultable sur demande.

---

### 12. Nous contacter

Pour toute question relative à cette politique ou pour exercer vos droits :

**Email :** sessoujeandedieu@gmail.com  
**Responsable :** Jean de Dieu SESSOU  
**Adresse :** 17 rue Kouenou, Lomé, Togo

---

## Notes de conformité et checklist

### Lois applicables identifiées

| Pays                              | Loi                               | Autorité de contrôle                                    |
| --------------------------------- | --------------------------------- | ------------------------------------------------------- |
| **Togo** _(siège du responsable)_ | Loi n°2019-014 du 29 octobre 2019 | ARDP (Autorité de Régulation des Données Personnelles)  |
| Sénégal                           | Loi n°2008-12 du 25 janvier 2008  | CDP (Commission de Protection des Données Personnelles) |
| Côte d'Ivoire                     | Loi n°2013-450 du 19 juin 2013    | ARTCI                                                   |
| Bénin                             | Loi n°2009-09 du 22 mai 2009      | APDP                                                    |
| Burkina Faso                      | Loi n°010-2004/AN                 | CIL (Commission de l'Informatique et des Libertés)      |
| Mali                              | Loi n°2013-015                    | APDP                                                    |

> Si l'app devient accessible en France/UE (diaspora), le **RGPD** s'applique intégralement — prévoir une mise à jour majeure de cette politique.

### Checklist avant publication

- [x] Révision juridique effectuée
- [x] Adresse et email du responsable renseignés
- [x] Date d'entrée en vigueur renseignée (27 mai 2025)
- [ ] Héberger la politique sur une URL publique accessible (ex: she-want-me.app/privacy)
- [ ] Renseigner l'URL dans l'App Store Connect et Google Play Console
- [ ] Ajouter un lien vers la politique dans l'app (écran AgeGate, Onboarding, ou Paramètres)
- [ ] Décider et documenter les durées de rétention manquantes (sessions, signalements)
- [ ] Implémenter un moyen pour l'utilisateur de connaître son UID (pour exercer ses droits)
- [ ] Enregistrer le traitement auprès de l'ARDP (Togo) si requis

### Décisions restantes (à trancher avant mise en prod)

1. **Durée de rétention des sessions** : Recommandé 30-90 jours. À documenter dans Firebase rules.
2. **Durée de rétention des signalements** (Epic 2) : Recommandé 12 mois. À décider avant déploiement d'Epic 2.
3. **Vérification d'âge** : La déclaration sur l'honneur est-elle suffisante selon les marchés cibles ?
4. **Registre des traitements** : Un document interne listant tous les traitements est recommandé (et obligatoire dans certains pays).
