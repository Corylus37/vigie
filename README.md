# Vigie

Site du poste de vigie : un robot de suivi de tendance sur BTC, ETH et une 3e place tournante, avec un système
d'achat dans les krachs. Une décision par nuit, règle publique, défauts assumés.

- `index.html` : le site, une seule page sans dépendance à installer. Il embarque l'historique des clôtures
  Binance jusqu'au 14/11/2026 et le moteur de décision de Vigie 2 + krach (traduction fidèle du code du robot,
  vérifiée au centime près), puis complète en direct depuis l'API publique de Binance (clôtures et prix du moment).
- `journal.csv` : journal publié chaque nuit par le serveur de Vigie ; sert de secours si Binance est injoignable.
- `archive/vigie-1.html` : l'ancien site (Vigie 1, BTC/ETH/SOL), conservé.

Les chiffres longs proviennent de simulations sur données passées. Ils ne constituent ni un conseil en
investissement ni une promesse de résultat.
