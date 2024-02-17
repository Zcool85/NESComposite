# NESComposite

Projet permettant à une NES :
- de sortir le format vidéo composite (au lieu du RGB) sur la périmtel
- de sortir un son "stéréo" sur la péritel
- dézoner la console

[Documentation](https://zcool85.github.io/projects/NES-composite/)

Le présent repository se décompose en plusieurs parties :

- Composite video mod : Première version permettant de sortir le flux vidéo composite
  de la console. (Cette version me donne les meilleurs résultats)

  C'est cette version qui est utilisée pour remplacer le circuit RVB d'origine de la console tout en passant le signal
  dans la péritel d'origine de la console.
  
- Composite video mod v2 : Seconde version permettant de sortir le flux vidéo composite
  de la console. (Je ne constate pas d'amélioration avec ce schéma)

- Audio mod : Schéma de principe KiCad pour sortir le son en "stéréo"

- CIC mod : Explications pour dészoner la NES

- Remplacement RVB : Projet permettant de remplacer la carte RGB de la NES par une
  carte personnalisée avec une sortie composite uniquement
