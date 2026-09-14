# Aprendizaje Estadístico 2 (APE2)

Agrupa los talleres, parciales, recursos y el proyecto del curso.

## Autor

[JUAN SEBASTIÁN GUAYAZÁN CLAVIJO](https://github.com/JuanGuayazanC)  
Escuela Colombiana de Ingeniería Julio Garavito

## Estructura del proyecto

```
Aprendizaje-Estadistico-2/
├── Talleres/
│   ├── Taller-1-Espacio-Muestral-Moneda-APE2/
│   ├── Taller-2-Distribuciones-y-Probabilidad-APE2/
│   └── Taller-de-Repaso-Aproximacion-Normal-Binomial-APE2/
├── Parciales/
│   ├── Parcial-Distribucion-Muestral-y-TCL-APE2/
│   └── Parcial-Intervalos-de-Confianza-Diamonds-APE2/
├── Recursos/
│   ├── Distribuciones-Continuas-y-Probabilidad-Conjunta-APE2/
│   ├── Inferencia-Estadistica-Intervalos-y-TCL-APE2/
│   └── Pruebas-de-Hipotesis-y-Regresion-Lineal-APE2/
└── Proyectos/
    └── Percepcion-ciudadana-y-salud-mental-durante-la-cuarentena-por-COVID-19-en-Bogota-APE2/
```

## Temas del curso

- Distribuciones de probabilidad continuas y discretas (normal, gamma, exponencial, Poisson).
- Probabilidad conjunta: covarianza y correlación.
- Teorema del Límite Central.
- Intervalos de confianza para medias y proporciones poblacionales.
- Pruebas de hipótesis (diferencia de medias, chi-cuadrado).
- Regresión lineal simple.

## Cosas a tener en cuenta

- Cada repositorio corresponde a una actividad puntual (taller, parcial o recurso) o al proyecto del curso; el tipo de actividad está indicado en la descripción de cada repositorio, no en su nombre.
- Los recursos son ejercicios de clase trabajados a partir de material del profesor, sin entrega individual.
- Los talleres y parciales de equipo se entregaron junto con Gabriel Alejandro Rodríguez Pulido, Nicol Sofía Guerra Lasso, María Paula Bonilla Martínez y Jerónimo Esteban Quilaguy Torres, según la actividad.
- El proyecto del curso tiene una estructura de README distinta a la del resto de actividades académicas, ya que corresponde a un trabajo de análisis extendido y no a una entrega puntual.

## Profesor

Iván Mauricio Mendivelso Ramírez.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes, uno por actividad, organizados por carpetas (`Talleres/`, `Parciales/`, `Recursos/`, `Proyectos/`). Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Aprendizaje-Estadistico-2.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
