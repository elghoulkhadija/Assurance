# Dashboard Assurance Automobile - Maroc

Ce projet est un **dashboard interactif** pour la gestion des contrats d’assurance automobile au Maroc.  
Il permet d’importer un fichier Excel contenant les contrats, de filtrer les données, d’afficher des KPIs et d’exporter les informations au format **Excel**, **Word** et **PDF**.

---

## Fonctionnalités

1. **Importation Excel**
   - L’utilisateur peut importer un fichier Excel (.xlsx) contenant les données des clients et contrats.
   - Le dashboard lit le fichier et affiche immédiatement les données.

2. **Dashboard (KPI)**
   - Total des contrats
   - Prime totale
   - Prime moyenne
   - Valeur totale des véhicules

3. **Filtrage des données**
   - Par ville
   - Par type d’assurance
   - Par type de véhicule

4. **Tableau des contrats**
   - Affiche toutes les informations importées dans un tableau responsive.
   - Colonnes : ID, Nom, Ville, Assurance, Véhicule, Prime, Valeur, Date de souscription

5. **Export**
   - Export des données filtrées au format :
     - Excel (`.xlsx`)
     - Word (`.doc`)
     - PDF (`.pdf`)

---

## Technologies utilisées

- **HTML5 / CSS3**
- **Bootstrap 5** pour le design responsive
- **Font Awesome** pour les icônes
- **JavaScript / ES6**
- **XLSX.js** pour la lecture et l’écriture des fichiers Excel
- **jsPDF et jsPDF AutoTable** pour l’export PDF
- **FileSaver.js** pour l’export Word

---

## Installation et utilisation

1. **Télécharger le projet**
   ```bash
   git clone <URL_DU_PROJET>
