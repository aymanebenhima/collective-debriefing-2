# Mobile First Design & Responsive Design

## Objectif
Ce projet vise à vous valider l'assimilation des concepts de **Mobile First Design** et de **Responsive Design**. Vous commencerez par concevoir l'interface pour les appareils mobiles, puis vous l'adapterez progressivement pour les écrans plus larges (tablettes et desktops).

## Structure du projet
- `index.html` : Ce fichier contient le contenu de la page.
- `style-guide.md` : Ce fichier contient les directives concernant les polices et les couleurs à respecter dans votre projet.
- `design/` : Ce dossier contient les maquettes du projet pour les versions **mobile** et **desktop**.
- `assets/images/` : Ce dossier contient toutes les images utilisées dans le projet.

## Prérequis
Pour travailler sur ce projet, vous devez avoir installé les outils suivants :
- **VS Code** : Il est recommandé d'utiliser l'éditeur de code Visual Studio Code pour une meilleure productivité et intégration des outils.
- **Navigateurs web** : Chrome, Firefox, ou tout autre navigateur moderne pour tester votre design responsive.

## Instructions
1. **Cloner le projet** :
   Clonez le repository sur votre machine locale.
   ```bash
   git clone https://github.com/aymanebenhima/collective-debriefing-1.git
   cd collective-debriefing-1
   code .
   ```

2. **Structure mobile first** :
   - Commencez par styliser le site pour les petits écrans (comme les téléphones mobiles).
   - Utilisez des `@media queries` pour ajuster le design pour les écrans plus grands (tablettes et ordinateurs).
   - Les breakpoints principaux à utiliser peuvent être trouvés dans la section du **style-guide.md**.

3. **Respecter le style-guide** :
   - Le fichier `style-guide.md` contient les informations concernant les polices et les couleurs que vous devez utiliser pour que votre design soit conforme aux maquettes.
   - Utilisez les fonts et couleurs spécifiées dans ce fichier pour maintenir la cohérence visuelle.

4. **Maquettes** :
   - Les maquettes sont disponibles dans le dossier `design/`. Elles comprennent les versions mobile et desktop du site.
   - Veillez à suivre ces maquettes pour la création du layout et l'ajustement des éléments en fonction de la taille de l'écran.

5. **Tester le design responsive** :
   - Utilisez les outils de développement de votre navigateur pour tester le design sur différentes tailles d'écran.
   - Vérifiez que votre site fonctionne bien sur mobile, tablette, et desktop.

## Bonnes pratiques
- **Mobile first** : Écrivez d'abord les styles pour les petits écrans avant d'ajouter des styles pour les écrans plus larges.
- **Réutilisation des classes** : Utilisez des classes CSS communes pour ne pas dupliquer les styles.
- **Flexbox et Grid** : Utilisez des techniques modernes comme `flexbox` ou `grid` pour créer des layouts flexibles.

**Good Luck !**
