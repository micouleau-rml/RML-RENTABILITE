# RML Rentabilité Chantier

Application web statique créée à partir du fichier `RML_Renta.xlsx`.

## Installation sur GitHub Pages

1. Créer un dépôt GitHub, par exemple `rml-rentabilite`.
2. Envoyer tous les fichiers de ce dossier à la racine du dépôt.
3. Aller dans **Settings > Pages**.
4. Dans **Build and deployment**, choisir **Deploy from a branch**.
5. Sélectionner la branche `main` et le dossier `/root`.
6. Ouvrir l'adresse GitHub Pages générée.

## Fonctionnalités

- Création de plusieurs chantiers.
- Rentabilité estimée et rentabilité réelle.
- Catalogue fournitures importé depuis l'onglet `Fournitures` : 173 articles.
- Coût horaire vendu et frais généraux repris depuis l'onglet `Finances`.
- Sauvegarde locale dans le navigateur.
- Export/import JSON pour transférer les données entre Mac et iPhone.
- Impression ou export PDF via le navigateur.

## Limite importante

Cette version fonctionne sans serveur. Pour une vraie synchronisation automatique entre plusieurs appareils de l'entreprise, il faudra ensuite raccorder l'application à Supabase ou Firebase.
