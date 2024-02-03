# Paramètres généraux <br> VEUILLEZ ÊTRE PRUDENT, TOUTES LES ACTIONS SONT EFFECTUÉES À VOS PROPRES RISQUES !

### Désactivation du contrôle des comptes d'utilisateur

Dans la recherche "Panneau de configuration", sélectionnez les petites icônes. "Comptes d'utilisateurs", "Modifier les paramètres du contrôle des comptes d'utilisateur", changez en "Non recommandé".
<br><br>

### Panneau de configuration

MISE À JOUR : N'oubliez pas d'appliquer !
Sélectionnez les petites icônes, sélectionnez "Centre d'accessibilité":
Décochez les cases "Lire toujours à voix haute" et "Défiler toujours cette section".

- Optimisation des images à l'écran - décochez toutes les cases.
- Facilitation de l'utilisation du clavier:<br>
  / Configuration du pointeur - décochez toutes les cases et désactivez NUM LOCK ci-dessous ;<br>
  / Configuration du rebondissement des touches - décochez toutes les cases ;<br>
  / Configuration de la filtration de l'entrée - décochez toutes les cases.
- Utilisation de texte ou d'images au lieu de sons - sélectionnez "Non".
- Facilitation de l'utilisation des panneaux tactiles et des tablettes - changez "Lecteur d'écran" en "Non" (si pas de tablette et pas de restrictions auditives ou visuelles).
  <br><br>

### Désactivation de l'indexation du disque.

MISE À JOUR : ATTENTION ! Cela prend du temps.
Ouvrez "Ce PC", faites un clic droit sur le disque (C:) "Propriétés", décochez la case "Autoriser l'indexation du contenu des fichiers" - "Appliquer" / "à ce disque et à tous les fichiers et dossiers inclus" / "ignorer tout".
<br><br>

### Liste des services pouvant être désactivés dans Windows (fonctionnant en mode automatique)

MISE À JOUR : Les services sont collectés à partir de Windows 10-11, certains d'entre eux peuvent ne pas être disponibles sur la version 10 ou 11, tenez compte de ce facteur.<br>
Légende :<br>
(•) - désactivation réservée aux utilisateurs expérimentés.<br>
(\*) - services pouvant être désactivés.<br>

| #   | Nom du service                                                   | Propriété                                                                                                 |
| --- | :--------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------- |
| \*  | Service de santé de la mise à jour Microsoft                     | Si le programme Service de santé de la mise à jour Microsoft a été supprimé                               |
| \*  | Superfetch ou SysMain                                            | Peut être désactivé si un SSD est utilisé et que la mémoire vive est supérieure à 8 Go                    |
| •   | Service de remédiation Windows                                   | Si vous n'utilisez pas les mises à jour Windows                                                           |
| •   | Recherche Windows                                                | Si vous ne recherchez pas de fichiers via la recherche                                                    |
| •   | Service biométrique Windows                                      | Si vous n'utilisez pas de mots de passe, de codes PIN, d'empreintes digitales, Windows Hello              |
| •   | Courtier de surveillance de la plateforme System Guard           | Si vous ne vérifiez pas l'intégrité des fichiers système                                                  |
| \*  | Service d'assistant IP                                           | Si le protocole IPv6 n'est pas utilisé                                                                    |
| \*  | Gestionnaire d'impression                                        | S'il n'y a pas d'imprimante et que les fonctions d'impression, y compris en PDF, ne sont pas utilisées    |
| \*  | Gestionnaire de connexions à distance                            | Si l'accès distant via VPN n'est pas utilisé                                                              |
| \*  | Gestionnaire de cartes téléchargées                              | Si les cartes Windows ne sont pas utilisées                                                               |
| •   | Gestionnaire de comptes Web                                      | Si vous n'utilisez pas Microsoft Store et les applications téléchargées à partir de celui-ci              |
| •   | Isolation des clés CNG                                           | Si vous n'utilisez pas de mots de passe, de codes PIN, d'empreintes digitales, Windows Hello              |
| \*  | Utilisation des données                                          | Si les informations sur le trafic ne sont pas utilisées                                                   |
| •   | Suivi des liaisons modifiées par le client                       | Si le déplacement de fichiers NTFS sur le réseau local n'est pas utilisé                                  |
| •   | Module de support NetBIOS sur TCP/IP                             | Si le réseau local n'est pas utilisé                                                                      |
| \*  | Optimisation de la livraison                                     | Si les mises à jour Windows ne sont pas utilisées                                                         |
| \*  | Assistant de connexion Microsoft Account                         | Si vous n'utilisez pas de produits Microsoft                                                              |
| \*  | Synchronisation de nœud                                          | Si le courrier Windows n'est pas utilisé et que vous n'êtes pas connecté avec un compte Microsoft         |
| \*  | Service de données des capteurs                                  | Si une tablette n'est pas utilisée avec Windows                                                           |
| \*  | Service des capteurs                                             | Si une tablette n'est pas utilisée avec Windows                                                           |
| •   | Service de mise en cache des polices Windows                     | Si vous ne mettez pas à jour Microsoft Office                                                             |
| \*  | Service de licence du client (ClipSVC)                           | Si vous n'utilisez pas Microsoft Store et les applications téléchargées à partir de celui-ci              |
| \*  | Service de surveillance des capteurs                             | Si une tablette n'est pas utilisée avec Windows                                                           |
| •   | Service de plateforme des périphériques connectés                | Si vous ne utilisez pas : Les bureaux virtuels, Chronologie, Votre téléphone et Lumière nocturne          |
| •   | Service utilisateur de la plateforme des périphériques connectés | Si vous ne utilisez pas : Les bureaux virtuels, Chronologie, Votre téléphone et Lumière nocturne          |
| \*  | Service de stockage                                              | Si vous n'utilisez pas Microsoft Store et les applications téléchargées à partir de celui-ci              |
| •   | Nœud de service de diagnostic                                    | Si la surveillance des diagnostics de l'ordinateur au niveau du système d'exploitation n'est pas utilisée |
| \*  | Fonctionnalités de connexion des utilisateurs                    | Collecte et suivi des données par Microsoft Company                                                       |
| \*  | Centre de mises à jour Windows                                   | Si les mises à jour Windows et Microsoft Store ne sont pas utilisés                                       |

<br>

### Correction de la variation automatique de la luminosité

Informations pour les ordinateurs portables équipés de processeurs Intel :
Si la luminosité fluctue lorsque vous débranchez le chargeur, vous devez ouvrir le "Centre de contrôle graphique Intel", sélectionner "Système", "Alimentation" et dans la section "Économie d'énergie de l'écran", désactiver le commutateur.
<br><br><br><br><br><br><br><br><br><br>

# Windows 10 <br> VEUILLEZ ÊTRE PRUDENT, TOUTES LES ACTIONS SONT EFFECTUÉES À VOS PROPRES RISQUES !

### Désactivation des notifications du pare-feu Windows ou de Windows Defender

Win + R, tapez regedit et appuyez sur Entrée.<br>
Dans le chemin : Ordinateur\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender Security Center\Notifications<br>
Dans la fenêtre vide, cliquez avec le bouton droit, créez "Nouvelle valeur DWORD (32 bits)" et nommez-la DisableNotifications.<br>
Ensuite, ouvrez la valeur en double-cliquant dessus et définissez sa valeur sur 1, appliquez et redémarrez votre PC.
<br><br>

### Configuration des propriétés du système

MISE À JOUR : N'oubliez pas d'appliquer !<br>
Cliquez avec le bouton droit sur "Ce PC", puis sur "Propriétés".<br>
Dans le menu contextuel, ouvrez "Paramètres système avancés".

- Nom de l'ordinateur / choisissez un autre nom si vous le souhaitez.
- Performances / vous pouvez tout désactiver, cela n'affecte pas beaucoup le système, vous pouvez utiliser "Optimiser pour les performances" même sur des PC peu puissants.
- Protection du système / Activer la protection ! Allouez 7 à 12 Go de mémoire.
- Accès à distance (si vous ne souhaitez aucune connexion externe à votre PC, vous pouvez le désactiver).
  <br><br>

### PROGRAMME "Paramètres"

#### 1. Système

- Notifications et actions (peut être désactivé selon vos préférences) / là, vous pouvez également modifier les tuiles d'actions rapides selon vos besoins.
- Concentration (recommandé pour les utilisateurs expérimentés)
  Désactivez tous les interrupteurs et cochez. Dans ce même menu, "Personnaliser votre liste de priorités", désactivez les interrupteurs et supprimez toutes les applications.
- Alimentation et mode veille, configurez les valeurs dont vous avez besoin / Dans ce même menu, "Paramètres d'alimentation supplémentaires", une fenêtre de gestion de l'alimentation s'ouvrira - où vous pouvez définir la performance élevée (sur un ordinateur portable, cela consommera plus de batterie).
- Mémoire / Désactiver la "Gestion de la mémoire".
- Tablette ou Mode tablette (appliquer si l'écran n'est pas tactile) - ne jamais utiliser le mode tablette / Demander l'autorisation avant de basculer. Dans ce même menu, "Modifier les paramètres supplémentaires de la tablette" et désactivez tous les commutateurs.
- Multitâche - désactiver la ligne de temps.
- Fonctionnalités générales - Désactiver le "Transfert entre les appareils" (si la connexion en ligne entre le PC et le smartphone n'est pas utilisée).
- Presse-papiers - désactiver tous les interrupteurs et effacer les données. MISE À JOUR : (Le presse-papiers fonctionnera également lorsque vous utiliserez Ctrl + C).

#### 2. Personnalisation

- Couleurs / Désactiver l'effet de transparence.
- Écran de verrouillage - désactiver tous les interrupteurs.
- Thèmes / Vous pouvez activer les paramètres des icônes du bureau pour "Ce PC" et "Corbeille".

#### 3. Applications

- Applications et fonctionnalités - supprimez les programmes préinstallés inutiles.
- Applications par défaut - définir celles qui sont nécessaires.
- Cartes hors connexion - désactiver tous les interrupteurs et utiliser "Supprimer toutes les cartes".
- Démarrage - vous pouvez désactiver les programmes qui se lancent au démarrage du PC.

#### 4. Jeux

- Barre de jeu Xbox - désactiver tous les interrupteurs.
- Captures - si vous n'utilisez pas l'enregistrement d'écran, désactiver tous les interrupteurs.
- Mode jeu - activer.

#### 5. Fonctionnalités spéciales

- Narrateur d'écran - désactiver tous les interrupteurs (si le narrateur n'est pas utilisé).
- Fonctions vocales - désactiver tous les interrupteurs.
- Clavier - désactiver tous les interrupteurs.
- Souris - désactiver tous les interrupteurs.

#### 6. Confidentialité

MISE À JOUR : N'oubliez pas de cliquer sur "Modifier" et d'activer ou de désactiver en fonction de la situation.

- Général - désactiver tous les interrupteurs sauf "Autoriser Windows à suivre les lancements d'applications".
- Fonctions vocales - désactiver tous les interrupteurs.
- Personnalisation de l'écriture manuscrite - désactiver tous les interrupteurs.
- Diagnostics et commentaires - cocher "Données de diagnostic obligatoires". Ensuite, désactivez tous les autres paramètres. Fréquence des commentaires (jamais). Supprimer les données de diagnostic.
- Journal des activités - désactiver tous les interrupteurs et cases à cocher. Effacer le journal des activités.

<br>

ACTIVER TOUS LES AUTORISATIONS OU DÉSACTIVER TOUTES LES AUTORISATIONS DANS LES PERMISSIONS SUIVANTES :

| Nom de l'autorisation        | Action     |
| ---------------------------- | ---------- |
| Emplacement                  | ACTIVER    |
| Caméra                       | ACTIVER    |
| Microphone                   | ACTIVER    |
| Activation vocale            | Désactiver |
| Informations de compte       | Désactiver |
| Contacts                     | Désactiver |
| Calendrier                   | Désactiver |
| Appels téléphoniques         | Désactiver |
| Historique des appels        | Désactiver |
| Courrier électronique        | Désactiver |
| Tâches                       | Désactiver |
| Messagerie                   | Désactiver |
| Radio                        | Désactiver |
| Autres appareils             | Désactiver |
| Applications en arrière-plan | Désactiver |
| Diagnostic des applications  | Désactiver |
| Téléchargement automatique   | IGNORER    |
| Documents                    | ACTIVER    |
| Images                       | ACTIVER    |
| Vidéos                       | ACTIVER    |
| Système de fichiers          | ACTIVER    |

<br>

#### 7. Mise à jour et sécurité

- Centre de sécurité de Windows Update, à l'intérieur de "Paramètres avancés", désactivez tous les interrupteurs. À l'intérieur de "Optimisation de la distribution", désactivez le téléchargement à partir d'autres ordinateurs.
  <br><br>

### Désactivation de Microsoft Defender

Pour désactiver Microsoft Defender, ouvrez "Paramètres" / "Mise à jour et sécurité" / "Sécurité Windows" / "Ouvrir la Sécurité Windows".
"Protection contre les virus et menaces" / "Gérer les paramètres" et désactivez tous les interrupteurs.
MISE À JOUR : après le redémarrage de votre PC, Defender se réactivera.
<br><br><br><br><br><br><br><br><br><br>

# Windows 11 <br> BE CAREFUL ALL ACTIONS ARE TAKEN AT YOUR OWN RISK!

### System Properties Configuration

UPDATE: Don't forget to apply the changes!
Right-click on "This PC", select Properties.
This will open the settings, look for "Related Settings" and open "Additional system settings".

- Computer Name / Change it as desired.
- Additional / Performance can be adjusted, but it doesn't significantly affect the system. You can use "Adjust for best appearance" even on weaker PCs.
- System Protection / Turn on protection! Allocate 7-12 GB of memory.
- Remote access (If you don't want any connections to the PC from outside, you can disable it.)

---

### SETTINGS App

#### 1. System

- Notifications (Optional to disable), but it's better to leave it on.
- Power & sleep, set values as per your requirement. In the "Power mode" menu, select "Best performance" (it will consume more battery on laptops).
- Memory / Turn off "Memory integrity".
- Nearby sharing - disable (If you're not using online connections between PC and smartphone).
- Troubleshoot - Change to "Ask me before running".
- Clipboard, turn off "Clipboard history" and clear data. UPDATE: (Clipboard will still work when using Ctrl + C).

#### 2. Personalization

- Colors / Turn off Transparency effects.
- Themes / Desktop icon settings can be adjusted. Add "This PC" and "Recycle Bin".
- Lock screen / Turn off all toggles and switches. Lock screen status - "None".
- Start / Use "More pinned tiles". Turn off all toggles.
- Taskbar / You can turn off all toggles as per your preference.
- Device usage / Turn off all toggles.

#### 3. Apps

- Installed apps - Uninstall pre-installed programs that are not needed.
- Default apps can be set as needed.
- Offline maps - Disable toggles. Uncheck "Automatically update".
- Startup - You can disable programs that launch at PC startup.

#### 4. Gaming

- Xbox Game Bar - Disable.
- Captures - If you're not using screen recording, turn off all toggles.
- Gaming mode - Turn on.

#### 5. Special features

- Narrator - Disable all toggles and checkboxes (if Narrator is not used).
- Voice typing - Turn off all toggles.
- Keyboard - Turn off all toggles. UPDATE: "Use the PrtSc key to open screen snipping" can be left on as desired.
- Mouse - Turn off all toggles.

#### 6. Privacy

- General - Turn off all toggles except "Let Windows track app launches".
- Voice - Turn off all toggles.
- Handwriting personalization - Turn off all toggles. "Clear custom dictionary".
- Diagnostics & feedback - Turn off all toggles and Delete diagnostic data. Feedback frequency (Never).
- Activity history - Turn off all toggles. Clear activity history.

<br>

ENABLE ALL PERMISSIONS OR DISABLE ALL PERMISSIONS IN THE FOLLOWING:

| Permission Name       | Action  |
| --------------------- | ------- |
| Location              | ENABLE  |
| Camera                | ENABLE  |
| Microphone            | ENABLE  |
| Voice activation      | Disable |
| Notifications         | ENABLE  |
| Account info          | Disable |
| Contacts              | Disable |
| Calendar              | Disable |
| Call history          | Disable |
| Email                 | Disable |
| Tasks                 | Disable |
| Messaging             | Disable |
| Radios                | Disable |
| Other devices         | Disable |
| App diagnostics       | Disable |
| Automatic downloads   | SKIP    |
| Documents             | ENABLE  |
| Downloads folder      | ENABLE  |
| Music library         | ENABLE  |
| Pictures              | ENABLE  |
| Videos                | ENABLE  |
| File system           | ENABLE  |
| Screen snipping frame | ENABLE  |
| Screen & app captures | ENABLE  |

<br>

#### 7. Windows Update Center

- "Additional settings" turn off all toggles. Inside "Delivery optimization", turn off the option to download from other computers.

---

### Disabling Microsoft Defender

To disable Microsoft Defender, open "Settings" / "Privacy & Security" / "Windows Security" / "Open Windows Security".
"Virus & threat protection" / "Manage settings", disable all toggles.
UPDATE: After restarting your PC, Defender will be re-enabled.
