# Pointeo

**Mettez en évidence votre curseur et vos clics, annotez l'écran et dessinez sur un tableau, pour vos présentations, tutoriels et démos.**

Utilitaire Windows léger. Tout reste sur votre ordinateur : Pointeo n'effectue aucune requête réseau.

<p align="center">
  <a href="https://github.com/Isma0216/Pointeo-releases/releases/latest">
    <img alt="Télécharger Pointeo" src="https://img.shields.io/github/v/release/Isma0216/Pointeo-releases?label=T%C3%A9l%C3%A9charger&style=for-the-badge&color=2563eb">
  </a>
</p>

<p align="center"><a href="https://github.com/Isma0216/Pointeo-releases/releases/latest"><b>➜ Télécharger la dernière version</b></a></p>

---

## Fonctionnalités

| | |
|---|---|
| **Anneau autour du curseur** | Un cercle coloré suit le curseur pour que votre public ne le perde jamais. Taille, couleur et opacité réglables. Secouez la souris : l'anneau grossit un instant pour vous retrouver, même s'il est désactivé. |
| **Ondes au clic** | Un rond s'anime à chaque clic. Couleur réglable pour chaque bouton (gauche, droit, molette), taille et durée ajustables. |
| **Dessin à l'écran** | Stylo, surligneur, flèche, ligne, rectangle, ellipse et gomme, directement par-dessus n'importe quelle application. Palette de couleurs personnalisable, annuler / rétablir, et un mode « maintenir une touche » pour dessiner le temps d'un geste. |
| **Tableau** | Une page blanche (ou d'un autre fond) en plein écran pour dessiner et écrire du texte. Elle est enregistrée automatiquement et vous la retrouvez à la prochaine ouverture. |
| **Projecteur** | L'écran s'assombrit sauf un cercle autour du curseur, pour attirer l'attention sur un point précis. |
| **Touches affichées** | Les touches pressées apparaissent à l'écran, idéal pour les tutoriels. Deux modes : raccourcis uniquement (Ctrl, Alt, Win + touche…), ou toutes les touches. Le texte tapé dans un champ de mot de passe n'est jamais affiché. |
| **Profils** | Enregistrez plusieurs configurations (ex. « Présentation », « Tuto ») et passez de l'une à l'autre en un raccourci. |
| **Raccourcis clavier** | Tout se pilote au clavier, et chaque raccourci est modifiable. |
| **Exclusions** | Pointeo se masque automatiquement devant les applications en plein écran (jeux, vidéos) et devant celles que vous excluez. Les logiciels de présentation (PowerPoint, LibreOffice Impress) restent couverts. |

Interface en français et en anglais, thème clair ou sombre, icône dans la zone de notification avec un panneau de réglages rapides.

### Raccourcis par défaut

| Action | Raccourci |
|---|---|
| Activer / désactiver l'anneau | `Ctrl+Alt+R` |
| Agrandir / réduire l'anneau | `Ctrl+Alt+↑` / `Ctrl+Alt+↓` |
| Activer / désactiver les ondes au clic | `Ctrl+Alt+C` |
| Mode dessin | `Ctrl+Alt+D` (ou maintenir `Ctrl` droit) |
| Tout effacer | `Ctrl+Alt+X` |
| Ouvrir / masquer le tableau | `Ctrl+Alt+B` |
| Projecteur | `Ctrl+Alt+S` |
| Profil suivant | `Ctrl+Alt+P` |
| Pause globale (tout masquer) | `Ctrl+Alt+Q` |

## Téléchargement

Rendez-vous sur la page de la **[dernière version](https://github.com/Isma0216/Pointeo-releases/releases/latest)** et choisissez :

| Fichier | Pour qui | Détails |
|---|---|---|
| `Pointeo-Setup-<version>.exe` | **Recommandé** | Installeur. Pas besoin de droits administrateur, raccourci dans le menu Démarrer, désinstallation propre. Démarrage rapide, environ 45 Mo de mémoire. |
| `Pointeo-<version>-portable.exe` | Clé USB, poste sans installation | Un seul fichier, rien à installer : double-cliquez et c'est parti. Plus lourd en mémoire (environ 105 Mo), car il se décompresse au lancement. |

Le fichier `SHA256SUMS.txt` joint à chaque version permet de vérifier l'intégrité des téléchargements :

```powershell
Get-FileHash .\Pointeo-Setup-0.9.0.exe -Algorithm SHA256
```

### Prérequis

- Windows 10 21H2 ou plus récent, ou Windows 11, **64 bits (x64)**
- **Pas besoin d'installer .NET** : tout est inclus.

### Avertissement Windows SmartScreen

Pointeo n'étant pas encore signé numériquement, Windows peut afficher « Windows a protégé votre ordinateur » au premier lancement. Cliquez sur **Informations complémentaires › Exécuter quand même**.

## Vos données

Aucune requête réseau, aucune télémétrie. Les réglages, le tableau et les journaux restent dans `%AppData%\Pointeo`. À la désinstallation, vous choisissez de les conserver ou de les supprimer.

## Licence

© 2026 Ismaël Zerouali – Tous droits réservés.

Pointeo est un **logiciel propriétaire**, distribué gratuitement sous forme d'exécutables. Son code source n'est pas public. Toute reproduction, modification, redistribution ou rétro-ingénierie sans autorisation écrite de l'auteur est interdite. Le logiciel est fourni « tel quel », sans garantie d'aucune sorte.

---

## English summary

**Pointeo** is a lightweight Windows utility for presentations, tutorials and demos. It highlights your cursor with a ring, animates your clicks, lets you draw on the screen (pen, highlighter, arrow, shapes, eraser) or on a full-screen whiteboard, dims the screen around the cursor (spotlight), and shows the keys you press on screen. Settings can be saved as profiles, and every action has a customizable keyboard shortcut. Pointeo makes no network requests.

- **Download:** [latest release](https://github.com/Isma0216/Pointeo-releases/releases/latest). Choose `Pointeo-Setup-<version>.exe` (installer, recommended, no admin rights needed) or `Pointeo-<version>-portable.exe` (single file, no installation, uses more memory).
- **Requirements:** Windows 10 21H2+ or Windows 11, 64-bit (x64). No .NET installation needed.
- **SmartScreen:** if Windows shows "Windows protected your PC", click **More info › Run anyway**.
- **License:** © 2026 Ismaël Zerouali – All rights reserved. Proprietary software, free to use; the source code is not public.
