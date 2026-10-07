# Airbnb NYC Pricing Analysis

Data analysis of Airbnb listings in New York City (2019) to test four pricing decisions that the commercial team had proposed without data: a price range of USD 25–1,900, an average price of USD 225, automatic discounts for long stays, and a single rate for Brooklyn and Manhattan.

## Key findings

| Proposal | What the data shows | Recommendation |
|---|---|---|
| Price range USD 25–1,900 | 90% of prices fall in a narrower range | Adjust to USD 40–1,500 |
| Average price USD 225 | The real average is USD 152.72 | Target USD 150–160 |
| Discounts by length of stay | Very low correlation between number of nights and price | Do not apply automatic discounts based only on length of stay |
| Same rate for Brooklyn and Manhattan | Manhattan prices are about 40% higher | Keep differentiated rates |

## Method

1. **Data cleaning:** treatment of missing values (mean or mode; forward fill for dates).
2. **Exploratory data analysis:** price distribution, relationship between length of stay and price, and comparison between boroughs.
3. **Visualization:** histograms, box plots, violin plots and scatter plots in Python, plus a Power BI report.

## Files

| File | Content |
|---|---|
| `analisis reto 1.pdf` | Python analysis (exported notebook): cleaning, EDA and conclusions |
| `reto1.pdf` | Power BI report: prices by borough and rate-unification analysis |
| `AB_NYC_2019.csv` | Original dataset |

**Tools:** Python (pandas, NumPy, Matplotlib, seaborn), Power BI.

---

### En español

Análisis de los datos de Airbnb en Nueva York (2019) para validar cuatro decisiones de precios que el equipo comercial había propuesto sin respaldo en datos. Conclusiones: ajustar el rango de precios a USD 40–1.500, fijar el precio promedio objetivo en USD 150–160 (el real es USD 152,72), no aplicar descuentos automáticos solo por duración de la estadía (la correlación entre noches y precio es muy baja) y mantener tarifas distintas para Manhattan y Brooklyn (Manhattan es cerca de 40% más caro). El análisis en Python está en `analisis reto 1.pdf` y el informe de Power BI en `reto1.pdf`.
