# Super prompt: «CI forense, qué significa cada cifra»

Actúa como un equipo de tres personas: una psicometrista clínica (escalas Wechsler, WAIS-IV, WAIS-5, WISC-V), un periodista de datos que revisa cada número contra fuentes primarias y un diseñador de producto de Apple.

## Encargo
Haz una investigación forense del coeficiente intelectual (CI) y explica qué significa cada cifra: el puntaje total, cada tramo de la escala y cada número de un informe real de evaluación.

## Lo que tiene que responder
1. **De dónde sale el número.** El CI de desviación: media 100 y desviación estándar 15. Por qué ya no se calcula como edad mental ÷ edad cronológica × 100 (Stern y Terman).
2. **Cada tramo, cifra por cifra.** 40, 55, 70, 85, 100, 115, 130, 145 y 160: el percentil de cada uno, cuántas personas de cada 1.000 quedan por debajo, la etiqueta descriptiva (Wechsler) y lo que eso significa y no significa en la práctica.
3. **El informe por dentro.** Los índices del WAIS-IV y de la nueva WAIS-5 (comprensión verbal, razonamiento perceptivo/visoespacial y fluido, memoria de trabajo, velocidad de procesamiento), las puntuaciones escalares de 1 a 19 (media 10, DE 3), el percentil, el intervalo de confianza al 95 % y el error típico de medida.
4. **Por qué un CI no es una cifra exacta.** El intervalo de ±5 a 7 puntos, la diferencia entre pruebas, el efecto Flynn (~3 puntos por década), la normalización por país y edad, y lo que ocurre por encima de 145 o por debajo de 55.
5. **Mitos.** «Einstein tenía 160», «el CI no cambia», «un test online mide CI», «el CI lo explica todo».
6. **Herramienta.** Una calculadora interactiva: escribes un CI y te devuelve percentil, rareza, etiqueta e intervalo de confianza.

## Reglas
- Cada cifra se calcula (curva normal) o se cita de una fuente primaria: manuales de Wechsler y Pearson, APA, DSM-5-TR, Flynn. No inventar datos.
- Español de Chile, claro, sin jerga sin explicar y sin estigmatizar.
- Aclarar que es divulgación: un CI solo lo puede determinar una evaluación profesional.

## Entrega
- Sitio estático de una página, estilo Apple en blanco: mucho aire, tipografía grande del sistema (SF Pro / Inter), negro sobre blanco, un único color de acento, animaciones suaves al hacer scroll y respeto por `prefers-reduced-motion`. Que funcione bien en el teléfono.
- Gráfico de la campana dibujado en SVG, con los tramos marcados.
- Repositorio público en GitHub y producción en Vercel conectada al repo (cada push a `main` despliega).
