# Ayudantías de Organización Industrial

Compilado de ejercicios con solución de **Microeconomía II (MIC355) – Organización Industrial**, pensado como insumo para ayudantías de este curso o de cursos relacionados.

📄 **[Descargar el PDF](ejercicios.pdf)**

## Contenido

| Unidad | Tema |
|:--:|---|
| I | Competencia à la Cournot |
| II | Competencia à la Bertrand |
| III | Cournot versus Bertrand |
| IV | Stackelberg y juegos secuenciales |
| V | Colusión y juegos repetidos |
| VI | Diferenciación de productos |
| VII | Monopolio multiproducto |
| VIII | Concentración, poder de mercado y fusiones |
| IX | Discriminación de precios |
| X | Venta atada, empaquetamiento y disuasión de entrada |
| XI | Entrada y amenazas creíbles |
| XII | Restricciones verticales y doble marginalización |
| XIII | Subastas |

## Estructura

```
ejercicios.pdf      # versión compilada
tex/
├── ejercicios.tex  # documento principal
├── u*_*.tex        # una unidad por archivo
└── escudo.jpg
```

## Compilar

Requiere una distribución LaTeX con `latexmk`:

```sh
cd tex
latexmk -pdf ejercicios.tex
```

## Contacto

joamartine@fen.uchile.cl
