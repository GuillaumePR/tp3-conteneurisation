# tp3-conteneurisation

3 optimisations :
- multi-stage build qui sépare les installs et reduit la taille de l’image final
- utiliser node:20-alpine pour une image plus légère et plus rapide (et donc tous les avantages qui vont avec ça)
- 'npm ci' au lieu de 'npm install' : intall basé sur package lock donc build plus rapide 
