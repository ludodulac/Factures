# Mes factures — Ludovic

Application statique et personnelle pour créer des factures PDF depuis un téléphone Android.

- Entrée : **index.html**.
- Numéro automatique au format JJMMYYYY basé sur la date sélectionnée.
- Calcul automatique du montant, aperçu, téléchargement du PDF et partage mobile.
- Sauvegarde locale des informations via `localStorage`, avec import/export JSON.
- Mode hors connexion via Service Worker après première visite.
- Aucune dépendance, aucun backend, aucune donnée bancaire ou adresse personnelle stockée dans les fichiers publics du dépôt.

## Publication GitHub Pages

Settings → Pages → Build and deployment → Source = **Deploy from a branch**.

Sélectionnez **main** et le dossier **/(root)**, puis Save. Le site sera alors publié automatiquement.

Adresse prévue : https://ludodulac.github.io/Factures/

## Première utilisation

Importer la configuration personnelle JSON (conservée séparément du dépôt), ou ouvrir un lien de configuration personnel. Les champs sont ensuite sauvegardés dans le navigateur de l'appareil. Il faut sauvegarder un JSON avant d'effacer les données du navigateur.

**À vérifier avant l'envoi :** le numéro d'immatriculation, les obligations relatives à la facturation, et l'unicité des numéros si plusieurs factures partent le même jour.
