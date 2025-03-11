# Techniques d'augmentation des données pour les séries temporelles financières

## Contexte
 
Les modèles d'apprentissage automatique sont devenus essentiels pour analyser de vastes quantités de données financières, mais ils font face à des défis inhérents tels que la rareté des données, le bruit et la forte volatilité. Les modèles de séries temporelles financières, en particulier, sont souvent sujets au sur apprentissage en raison de données historiques limitées et déséquilibrées, rendant les prédictions robustes difficiles [1, 2]. L'augmentation de données, une technique traditionnellement utilisée en vision par ordinateur, offre une solution intéressante en générant des variations synthétiques des ensembles de données existants. Dans le contexte des produits financiers, cela peut signifier créer des simulations de séries temporelles réalistes ou introduire du bruit pour entraîner des modèles résilients aux fluctuations du marché. Malgré son potentiel, l'application de l'augmentation de données aux marchés financiers reste peu explorée [3].
 
## Objectif
 
Ce projet vise à évaluer l'impact de diverses techniques d'augmentation de données sur la performance prédictive des modèles d'apprentissage automatique dans les marchés financiers. Plus précisément, le projet cherche à (a) explorer et mettre en œuvre des méthodes d'augmentation de données adaptées aux séries temporelles financières, telles que l'ajout de bruit gaussien, la déformation temporelle, le bootstrapping, et la génération de données synthétiques à l'aide de GANs ou de simulations stochastiques ; (b) entraîner et évaluer des modèles d'apprentissage automatique (par exemple, Random Forest, LSTM, GRU) sur des ensembles de données d'origine et augmentés ; (c) quantifier les bénéfices de l'augmentation en comparant la performance des modèles à l'aide de métriques statistiques et financières, telles que la RMSE, la MAE et le ratio de Sharpe ; et (d) identifier les stratégies d'augmentation de données les plus efficaces pour des produits financiers spécifiques, tels que les actions, les ETF ou les cryptomonnaies.
 
## Références
 
[1] Y. El-Laham and S. Vyetrenko, “StyleTime: Style Transfer for Synthetic Time Series Generation,” in 3rd ACM International Conference on AI in Finance, 2022, pp. 489–496.
[2] G. Ranjbaran, D. R. Recupero, G. Lombardo, and S. Consoli, “Leveraging augmentation techniques for tasks with unbalancedness within the financial domain: a two-level ensemble approach,” EPJ Data Science, vol. 12, no. 1, p. 24, 2023.
[3] S. A. Assefa, D. Dervovic, M. Mahfouz, R. E. Tillman, P. Reddy, and M. Veloso, “Generating synthetic data in finance: opportunities, challenges and pitfalls,” in 1st ACM International Conference on AI in Finance, 2021.
