# Déjà vu

Plusieurs comptes Claude et ChatGPT dans une seule app Windows : les conversations et la mémoire
sont partagées entre les comptes, et quand l'un arrive à sa limite, un autre reprend la même
conversation.

*English below.*

## Installer

1. Télécharge `DejaVu-Setup-<version>.exe` dans la [dernière version](https://github.com/TheFrenchPepeAI/DejaVu/releases/latest).
2. Lance-le. L'installateur n'est pas signé : Windows peut afficher « Windows a protégé votre
   ordinateur ». Clique sur **Informations complémentaires**, puis **Exécuter quand même**.
3. Choisis le dossier d'installation, puis ouvre Déjà vu et ajoute tes comptes.

Il faut Windows 10 ou 11 (64 bits).

## Mises à jour

À partir de la 0.1.5, Déjà vu se met à jour tout seul : il regarde ici s'il y a une nouvelle
version, la télécharge en arrière-plan, puis propose **Redémarrer** sous la recherche (sinon elle
s'installe à la prochaine fermeture). Tes comptes, conversations et réglages restent.

Si tu as une version plus ancienne, installe la dernière à la main une fois, par-dessus.

## Désinstaller

Paramètres de Windows → Applications → Déjà vu → Désinstaller. Tes comptes et réglages restent
dans `%APPDATA%\deja-vu` : supprime ce dossier pour tout effacer.

## Un problème ?

Ouvre une [issue](https://github.com/TheFrenchPepeAI/DejaVu/issues) et joins le fichier
`%APPDATA%\deja-vu\logs\deja-vu.log` s'il existe.

---

## English

Several Claude and ChatGPT accounts in one Windows app: conversations and memory are shared
between the accounts, and when one reaches its limit, another picks up the same conversation.

- **Install:** download `DejaVu-Setup-<version>.exe` from the [latest release](https://github.com/TheFrenchPepeAI/DejaVu/releases/latest)
  and run it. The installer is not signed: if Windows says "Windows protected your PC", click
  **More info**, then **Run anyway**. Windows 10 or 11, 64-bit.
- **Updates:** from 0.1.5 on, Déjà vu updates itself from this page (a **Restart** button shows
  under the search box, or it installs when you close the app). Older versions: install the
  latest one by hand once.
- **Uninstall:** Windows Settings → Apps → Déjà vu. Your accounts and settings stay in
  `%APPDATA%\deja-vu`.
- **Problems:** open an [issue](https://github.com/TheFrenchPepeAI/DejaVu/issues) with
  `%APPDATA%\deja-vu\logs\deja-vu.log` if it exists.

The app speaks French and English (the flag next to « Déjà vu » switches).

---

Déjà vu est un projet indépendant, sans lien avec Anthropic ni OpenAI. Claude est une marque
d'Anthropic, ChatGPT une marque d'OpenAI.
*Déjà vu is an independent project, not affiliated with Anthropic or OpenAI.*
