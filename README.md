# vision-rgpd-releases

Releases publiques officielles de **Vision RGPD** — logiciel de conformité RGPD 100 % local pour Windows.

Fiche produit : https://www.vision-digital.fr/shop/vision-rgpd-votre-conformite-rgpd-sur-votre-pc-a-vie-56

## Télécharger

Dernière version (URL stable) :

**VisionRGPD.zip** — https://github.com/Cyberchoc/vision-rgpd-releases/releases/latest/download/VisionRGPD.zip

## Installation

1. Décompressez `VisionRGPD.zip` où vous voulez (clic droit, « Extraire tout… »).
2. Ouvrez le dossier `VisionRGPD` et lancez `VisionRGPD.exe`.

Gardez le dossier `_internal` à côté de `VisionRGPD.exe` : le logiciel en a besoin pour démarrer.

## Versions

Voir l'onglet Releases pour l'historique et les notes de version.

## Vérification d'intégrité (SHA256)

Chaque release publie le hash SHA256 du fichier. Vérifier avant exécution sous PowerShell :

```
Get-FileHash -Algorithm SHA256 .\VisionRGPD.zip
```

Le hash retourné doit correspondre exactement à celui annoncé dans les notes de la release.

## Avertissement SmartScreen

Windows SmartScreen peut afficher un avertissement au premier lancement (logiciel non signé numériquement). Cliquer **Informations complémentaires** puis **Exécuter quand même**.

## Support

Questions, bugs : https://www.vision-digital.fr/contactus

— Vision Digital
