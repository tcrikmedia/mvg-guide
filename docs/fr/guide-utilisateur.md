# 🇫🇷 Mobile Vault Guard (MVG) - Guide d'utilisation

[← Retour au README principal](../../README.md)

---

## 🚀 Installation initiale et configuration du compte

Étant donné que MVG fonctionne sur une **architecture stricte à connaissance zéro (Zero-Knowledge)**, l'intégralité du traitement s'effectue à 100 % localement sur votre appareil. Veuillez suivre l'ensemble de ces étapes pour activer le bouclier de sécurité.

1. **Télécharger l'application :** Installez la version officielle directement depuis le [Google Play Store](https://google.com).
2. **Initialiser l'utilisateur maître :** Lors du premier lancement, vous devez configurer l'**Utilisateur Maître (Master User)**. Ce compte fera office d'Administrateur principal du téléphone.
   * *Remarque : Par défaut, ce compte dispose du **niveau d'habilitation 5** (Clearance Level 5), et toutes les applications du téléphone seront automatiquement verrouillées pour une sécurité immédiate.*
3. **Remplir le formulaire :** Complétez le formulaire d'inscription avec toutes les informations requises. Veillez à noter vos identifiants maîtres en lieu sûr et hors ligne.
4. **Connexion :** Une fois le formulaire validé, connectez-vous à l'aide de vos nouveaux identifiants d'utilisateur maître.

---

## ⚙️ Configuration après connexion

Pour activer le bouclier de confidentialité, vous devez explicitement accorder les autorisations système et valider les modules de sécurité.

1. **Accepter les autorisations :** Dès que la connexion est réussie, cliquez sur le bouton **Accept & Configure** (Accepter et configurer) pour autoriser l'application à déployer ses outils de gouvernance.
2. **Activer les configurations :** Depuis le tableau de bord principal (Dashboard), appuyez sur les configurations affichées en **rouge** pour les activer.
3. **Verrouillage final :** 
   ⚠️ **Important :** Toutes les configurations doivent impérativement être activées pour que l'application puisse sécuriser et protéger pleinement votre téléphone contre tout accès non autorisé.

---

## 📸 Aperçu de l'application

Découvrez l'interface de MVG. Les captures d'écran ci-dessous sont chargées directement depuis le dossier de votre dépôt local.

<table>
  <tr>
    <td align="center" width="33%">
      <img src="../../images/fr/login.jpg" width="100%" alt="Écran de connexion" /><br />
      <b>Étape 1</b><br />Se connecter
    </td>
    <td align="center" width="33%">
      <img src="../../images/fr/dashboardzero.jpg" width="100%" alt="Écran Accepter et configurer" /><br />
      <b>Étape 2</b><br />Appuyer sur Accepter et configurer
    </td>
    <td align="center" width="33%">
      <img src="../../images/fr/dashboardbefore.jpg" width="100%" alt="Tableau de bord avec la configuration désactivée" /><br />
      <b>Étape 3</b><br />Tableau de bord avant l'activation de la configuration
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="../../images/en/accessibility1.jpg" width="100%" alt="Activer VaultGuard dans Accessibilité, partie 1" /><br />
      <b>Étape 4a</b><br />Ouvrir les paramètres d'accessibilité
    </td>
    <td align="center">
      <img src="../../images/en/accessibility2.jpg" width="100%" alt="Activer VaultGuard dans Accessibilité, partie 2" /><br />
      <b>Étape 4b</b><br />Sélectionner VaultGuard
    </td>
    <td align="center">
      <img src="../../images/en/accessibility3.jpg" width="100%" alt="Activer VaultGuard dans Accessibilité, partie 3" /><br />
      <b>Étape 4c</b><br />Activer le service
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="../../images/en/activateadmin.jpg" width="100%" alt="Activer la configuration administrateur" /><br />
      <b>Étape 5</b><br />Activer la configuration administrateur
    </td>
    <td align="center">
      <img src="../../images/fr/dashboardafter.jpg" width="100%" alt="Tableau de bord avec la configuration activée" /><br />
      <b>Étape 6</b><br />Tableau de bord après l'activation de la configuration
    </td>
    <td></td>
  </tr>
</table>

---

## 💡 Cas d'utilisation pratiques

Une fois toutes les configurations activées, voici les principaux scénarios d'utilisation pour adapter la sécurité de votre appareil à votre quotidien :

### 1. Tester la sécurité par défaut
Pour vérifier que votre bouclier de confidentialité fonctionne immédiatement après la configuration initiale :
* **Étape 1 :** Déconnectez-vous (Sign out) du tableau de bord de l'application MVG.
* **Étape 2 :** Essayez d'ouvrir ou d'accéder à n'importe quelle application sur votre téléphone mobile.
* **Le résultat :** Toutes les applications étant restreintes par défaut, MVG interceptera immédiatement la tentative et vous demandera de vous connecter avec votre niveau d'habilitation.
* **Pour déverrouiller :** Saisissez votre identifiant d'administrateur et votre mot de passe, puis validez avec l'authentification biométrique.

### 2. Configurer une sécurité personnalisée (Recommandé au quotidien)
Pour une sécurité optimale, **n'utilisez pas le compte Administrateur Maître pour vos tâches quotidiennes**. Créez plutôt un profil avec un niveau d'accès plus faible pour un usage régulier ou pour vos enfants :
* **Étape 1 :** Appuyez sur le **menu des trois points** (`...`) dans le coin, sélectionnez **User Management** (Gestion des utilisateurs), puis créez un nouvel utilisateur avec un niveau d'habilitation inférieur (par exemple L1 à L4).
* **Étape 2 :** Retournez dans le **menu des trois points** (`...`), sélectionnez **Firewall Governance** (Gouvernance du pare-feu), puis allez dans la section **App Firewall**.
* **Étape 3 :** Appuyez sur le **bouton Plus (+)**. Sélectionnez les applications spécifiques que vous ne souhaitez pas restreindre, puis définissez les applications verrouillées qui resteront accessibles avec le niveau d'habilitation du nouvel utilisateur que vous venez de créer. Enfin, déconnectez-vous.
* **Le résultat :** Les applications non restreintes seront accessibles directement sans vérification. Toutes les autres exigeront obligatoirement soit les identifiants d'habilitation du nouvel utilisateur, soit les accès de l'administrateur maître.

### 3. Configurer le verrouillage automatique (Autolock out)
Évitez qu'une personne tierce accède à vos données si vous laissez votre téléphone déverrouillé sans surveillance :
* **Étape 1 :** Allez dans le menu **Settings** (Paramètres) de l'application.
* **Étape 2 :** Configurez l'option **Autolock out** en définissant le délai d'inactivité souhaité avant déconnexion.
* **Le résultat :** Une fois ce délai écoulé, l'application vous déconnectera automatiquement. Vous devrez alors vous reconnecter avec le niveau d'habilitation approprié pour accéder à nouveau aux applications mobiles restreintes.

---

## 🗺️ Présentation détaillée des fonctionnalités

### 🛡️ Niveaux d'habilitation multiples (Clearance Levels)
* **Contrôle Administrateur Maître :** Utilise des paramètres stricts d'authentification locale.
* **Niveaux 1 à 5 :** Attribuez des niveaux d'accès restreints aux utilisateurs secondaires. Vous contrôlez précisément quels fichiers, photos et dossiers chaque profil est autorisé à consulter.
* **Mode Sécurisé pour Enfants :** Restreignez l'accès à certaines applications afin que vos enfants ne puissent ouvrir que les programmes que vous approuvez explicitement.

### 🔑 Gouvernance matérielle isolée
* **Verrouillage d'applications :** Intercepte instantanément les tentatives d'accès si le niveau d'habilitation de l'utilisateur actuel est insuffisant via l'API d'accessibilité Android.
* **Zéro Cloud :** Vos fichiers, mots de passe et journaux d'audit ne transitent jamais par des serveurs externes ou des réseaux tiers.
