# IPoM-Sentiment-Analysis
Ejemplo rápido de análisis de sentimiento para la nota de prensa del IPoM septiembre 2020.

Se realiza un análisis de sentimiento mediante dos modelos: [vaderSentiment](https://github.com/cjhutto/vaderSentiment) sobre una traducción al inglés ([deep-translator](https://github.com/nidhaloff/deep-translator)) y [pysentimiento](https://github.com/finiteautomata/pysentimiento) sobre el texto en idioma original.

El análisis está disponible en este [notebook](https://github.com/aastroza/IPoM-Sentiment-Analysis/blob/main/analisis-ejemplo.ipynb).

# Resultados

La frase más positiva del documento tiene un score de +0.8316:

'Estas tasas de crecimiento son coherentes con un escenario sanitario que permitirá el avance paulatino del desconfinamiento, donde los sectores económicos continuarán adaptando sus operaciones para desarrollar sus actividades y donde el crédito seguirá fluyendo para apoyar el proceso de recuperación.'

La frase más negativa del documento tiene un score de -0.8176:

'Por el lado de la demanda agregada, el consumo y la inversión se han deprimido ante la pérdida de ingresos, las limitaciones a la movilidad y el contacto entre personas y la alta incertidumbre.'


