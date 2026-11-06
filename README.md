# ¿Qué inversiones le habrían ganado a la inflación en Argentina durante 2025?

Proyecto desarrollado para la materia **Laboratorio de Métodos Cuantitativos Aplicados a la Gestión** de la Tecnicatura Universitaria en Gestión y Análisis de Datos en Organizaciones (UBA - FCE).

## Objetivo

Analizar el rendimiento de distintas alternativas de inversión disponibles en Argentina durante 2025 y determinar cuáles lograron superar la inflación.

Las inversiones evaluadas fueron:

- Plazo fijo tradicional
- Plazo fijo UVA
- Dólar oficial
- CEDEAR del ETF SPY (S&P 500)

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yFinance
- mplfinance
- Google Colab

## Resultados principales

Considerando una inflación acumulada de **31,55%** durante 2025:

| Inversión | Rendimiento real |
|------------|------------:|
| SPY (en pesos) | +20,61% |
| Plazo fijo tradicional | +5,75% |
| Dólar oficial | +2,27% |
| Plazo fijo UVA | -0,28% |

## Contenido del repositorio

- **notebook_inversiones.ipynb**: notebook principal con el análisis completo, procesamiento de datos, simulaciones y visualizaciones.
- **Informe_Inversiones_vs_Inflacion_2025.pdf**: informe académico final con metodología, resultados y conclusiones.
- **Archivos CSV**: datasets utilizados para el análisis (IPC, UVA, plazo fijo, dólar y SPY).
- **Imágenes**: gráficos generados durante el desarrollo del proyecto.

## Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/fnlopezsanz/TP_Lab_Met_Cuantitativos_Inversiones.git
```

2. Instalar las dependencias:

```bash
pip install pandas numpy matplotlib seaborn yfinance mplfinance
```

3. Abrir y ejecutar el archivo:

```text
notebook_inversiones.ipynb
```

Puede ejecutarse tanto en **Google Colab** como en **Jupyter Notebook**.

## Autores

- Facundo Carrizo
- Facundo López Sanz
- Nicolás Javier Nozyce
- Lázaro Chaves de la Cruz
- Matías Peralta