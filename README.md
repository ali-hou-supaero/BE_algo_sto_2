# Descente de gradient stochastique et régression logistique

Bureau d’études ISAE-SUPAERO réalisé par **Ali Houssenaly et Maël Dacher**, consacré aux méthodes de gradient stochastique en apprentissage automatique.

## Parcours du notebook

- Étude d’un exemple d’optimisation simple et de l’influence du pas.
- Moyennisation de Polyak-Ruppert.
- Application à des modèles de régression logistique.

Le notebook [HOUSSENALY_DACHER_BE2.ipynb](HOUSSENALY_DACHER_BE2.ipynb) contient les questions, développements, implémentations et graphiques. `algo_sto.pdf` est un document associé au cours.

## Données et utilisation

Les fichiers d’images et d’étiquettes au format IDX compressé sont conservés à la racine (`train-*.gz` et `t10k-*.gz`). Le notebook utilise `gzip` pour leur lecture : les conserver compressés et lancer Jupyter depuis la racine.

```sh
python -m pip install jupyterlab numpy matplotlib
python -m jupyterlab
```

Ouvrir le notebook et exécuter les cellules dans l’ordre. Les dépendances ci-dessus correspondent aux imports examinés ; leurs versions ne sont pas figées. Aucune nouvelle exécution ni mesure de précision n’a été effectuée pour cette mise à jour documentaire.

## Attribution

Le dépôt conserve le support du bureau d’études et les réponses des auteurs ; les consignes pédagogiques restent distinctes des contributions étudiantes.
