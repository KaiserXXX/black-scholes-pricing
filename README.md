# Black-Scholes Option Pricing

Ce dépôt contient une implémentation simple du modèle Black-Scholes pour calculer le prix d'une option européenne (call).

## 📈 Modèle utilisé
Formule classique de Black-Scholes avec :
- Prix actuel de l’actif
- Strike
- Taux d’intérêt
- Volatilité
- Temps restant avant échéance

## 🛠️ Exemple de code

```python
from bs_pricing import black_scholes_call

price = black_scholes_call(100, 110, 1, 0.05, 0.2)
print(price)
