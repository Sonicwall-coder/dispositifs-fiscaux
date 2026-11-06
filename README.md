# Dispositifs fiscaux

Base ouverte des dispositifs fiscaux français utiles à un patrimoine de particulier (épargne, retraite, réductions
d'impôt, transmission, immobilier), tenue à jour par une veille automatique et utilisée par l'app Mes Comptes.

- **Information, pas un conseil** : chaque fiche résume des textes officiels ; elle ne remplace ni un notaire ni un
  conseiller.
- **Aucune donnée personnelle** : ce dépôt ne contient que des règles publiques.
- **Sources officielles obligatoires** : Légifrance, BOFiP, impots.gouv.fr, service-public.gouv.fr. Une fiche sans
  l'une d'elles a le statut `à confirmer`.

## Contenu

- `index.json` : liste des fiches et date de la base.
- `dispositifs/<id>.json` : une fiche par dispositif, au format décrit dans `schema.json`.
- `glossaire.json` : les mots techniques expliqués simplement.
- `journal.json` : chaque passage de la veille (date, moteur, consommation, changements).
- `vus.json` : les nouveautés officielles déjà examinées par la veille.
