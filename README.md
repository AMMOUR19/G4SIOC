# TP d'initiation à Julia et JuMP

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mathieuLacroix/G4SIOC/master)

Ce dépôt contient les supports de TP pour le module d'OC de l'institut Galilée (2ème année).

Contributeurs :

* Roland Grappe
* Mathieu Lacroix


Pour cloner le dépôt la première fois : 
```bash
git clone https://github.com/mathieuLacroix/G4SIOC.git
```

Pour lancer les notebooks julia :

1. Ouvrir un terminal et exécuter les commandes suivantes :
   ```bash
   cd G4SIOC
   julia
   ```
2. Exécuter le code julia suivant :
   ```julia
   using IJulia
   notebook()
   ```

*Remarque :* le noyau (kernel) doit être julia1.2. Si le noyau spécifié est python, vous devez changer le noyau.



Pour obtenir les nouveaux tps, taper dans le répertoire G4SIOC :

```bash
./updateDepot
```

Cette mise-à-jour automatique se fait via le script `pull.py` provenant du projet [nbgitpuller](https://github.com/jupyterhub/nbgitpuller/).
