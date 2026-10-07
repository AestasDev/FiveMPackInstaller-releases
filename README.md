# FiveM Pack Installer

**Installe un pack graphique dans FiveM en le glissant dans une fenêtre — et retire-le d'un clic.**

Le logiciel lit le pack, range chaque fichier à sa place (FiveM ou GTA V), te montre la liste avant de
copier quoi que ce soit, et sauvegarde tous les fichiers qu'il remplace. Ton jeu d'origine n'est
jamais perdu.

![Un pack lu, prêt à être installé](images/pack.png)

## ⬇️ Télécharger

**[Télécharger la dernière version](https://github.com/AestasDev/FiveMPackInstaller-releases/releases/latest)**
— prends le fichier `FiveMPackInstaller-Setup-….exe` dans la section « Assets ».

Windows 10 ou 11 (64 bits) · FiveM installé · environ 32 Mo

## Ce qu'il fait

- **Dépose ton pack** (`.zip`, `.rar`, `.7z` ou dossier) : chaque fichier est rangé automatiquement,
  même quand le pack mélange des dossiers « FIVEM », « GTA5 » et des emballages au nom libre.
- **Tu vérifies avant d'installer** : la liste montre où va chaque fichier, et tu peux en changer la
  destination d'un clic. Les programmes (`.exe`, `.bat`, scripts…) sont bloqués, jamais copiés.
- **Tout se défait** : chaque installation est sauvegardée dans l'Historique et se désinstalle d'un
  clic. « Tout remettre d'origine » rend un jeu propre.
- **Il voit un pack déjà posé à la main**, avant ce logiciel, et peut le mettre de côté proprement.
- **ReShade** : il vérifie qu'il est installé, et l'installe au besoin depuis le site officiel.
- **Cache de FiveM** : vide les logs, les crashs et les données temporaires, sans toucher aux
  fichiers du jeu.

![Historique des installations](images/historique.png)

## Installation

1. Télécharge `FiveMPackInstaller-Setup-….exe` (lien ci-dessus).
2. Lance-le. Windows peut afficher **« Windows a protégé votre ordinateur »** : le logiciel n'est pas
   signé numériquement. Clique sur **Informations complémentaires**, puis **Exécuter quand même**.
3. Accepte les [conditions d'utilisation](CONDITIONS-UTILISATION.txt) et suis l'assistant.
4. Le logiciel demande les droits administrateur à chaque lancement : c'est normal, il écrit dans les
   dossiers de FiveM et de GTA V.

Une nouvelle version s'installe par-dessus l'ancienne : tes réglages, ta licence et ton historique
sont conservés.

## Licence et abonnement

L'installation de packs demande un abonnement. Au premier lancement, la fenêtre d'activation affiche
**l'identifiant de ton ordinateur** : envoie-le à AestasFR par le canal où tu achètes ta licence, tu
recevras une clé faite pour ta machine.

Même sans licence, ou après la fin de ton abonnement, **tu peux toujours désinstaller tes packs et
restaurer tes fichiers d'origine.**

## Bon à savoir

- Ferme FiveM et GTA V avant d'installer ou de désinstaller un pack.
- Beaucoup de serveurs FiveM interdisent ReShade ou ENB : vérifie leur règlement.
- Ne joue pas à GTA Online avec des fichiers de GTA V modifiés : Rockstar sanctionne les comptes.
- Le logiciel fonctionne hors ligne et n'envoie aucune donnée.

## Vérifier le fichier téléchargé

Chaque version publie l'empreinte SHA-256 de son installateur dans ses notes de version. Pour la
comparer, dans PowerShell :

```
Get-FileHash .\FiveMPackInstaller-Setup-0.7.0.exe -Algorithm SHA256
```

---

FiveM Pack Installer n'est ni affilié, ni approuvé par Rockstar Games, Take-Two Interactive, Cfx.re
ou l'auteur de ReShade. © 2026 AestasFR — tous droits réservés.
