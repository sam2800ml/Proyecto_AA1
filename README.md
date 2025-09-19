Taller final prediccion y clasificacion en la industria azucarera

- A00417411 Alejandra Forero Rodríguez
- A00423284 Santiago Aristizabal Morales
- A00417017 Jose Luis Realpe Muñoz

1. Regresion -> predecir dos variables claves
    - Toneladas de caña por hectarea (TCH)
    - Porcentaje de sacarosa
    - Instrucciones: Realizar un Eda, identificar variables relevantes, visualizar la distribucion de las variables
    - Ajustar modelos de regresion lineal para la prediccion, analizar las significancias de las variables, interpretar los coeficientes y evaluar supuestos
    - Utilizar tecnicas de validacion, uar diferentes metricas de evaluacion

2. Diccionario Diccionario de Datos – HISTORICO_SUERTES
# 📖 Diccionario de Datos - HISTORICO_SUERTES

Este diccionario describe las variables presentes en la base de datos.

---

## 🔹 Variables Numéricas

| Columna                        | Descripción                                                                 |
|--------------------------------|-----------------------------------------------------------------------------|
| Periodo                        | Identificador del periodo o ano de registro.                                |
| Hacienda                       | Código o identificador de la hacienda (finca o plantación).                 |
| Tenencia                       | Forma de tenencia de la tierra (propiedad, arrendamiento, etc.).            |
| Area Neta                      | Área útil o neta destinada al cultivo (hectáreas o m²).                      |
| Dist Km                        | Distancia en kilómetros (posiblemente a planta procesadora u otro punto).   |
| Cod.Estado #                   | Código que representa el estado del cultivo.                                |
| Edad Ult Cos                   | Edad del cultivo en el momento de la última cosecha (días/semanas).         |
| Destino 1=Semilla              | Indicador de destino (ej. si se destinó a semilla).                         |
| Cod. T.Cultivo                 | Código del tipo de cultivo plantado.                                        |
| Dosis Madurante                | Dosis de insumo aplicado en la maduración.                                  |
| Semanas mad.                   | Número de semanas hasta alcanzar la madurez.                               |
| TonUltCorte                    | Toneladas obtenidas en el último corte.                                     |
| TCH                            | Toneladas de caña por hectárea (productividad).                             |
| TCHM                           | Variación de TCH (promedio o ajustado).                                     |
| Ton.Azucar                     | Toneladas de azúcar extraídas.                                              |
| Rdto                           | Rendimiento general del cultivo.                                            |
| TAH                            | Toneladas de azúcar por hectárea.                                           |
| TAHM                           | Variación de TAH (promedio o ajustado).                                     |
| Sac.Caña Precosecha            | Sacarosa estimada antes de la cosecha.                                      |
| Edad.Precosecha                | Edad del cultivo al momento de precosecha.                                  |
| %Sac.Caña                      | Porcentaje de sacarosa en la caña.                                          |
| %Sac.Muestreadora              | Porcentaje de sacarosa medido en muestreo.                                  |
| %ATR                           | Azúcares totales recuperables (porcentaje).                                 |
| KATRHM                         | Índice relacionado con ATR.                                                 |
| %Fibra Caña                    | Porcentaje de fibra presente en la caña.                                    |
| %AR Jugo                       | Porcentaje de azúcares reductores en jugo.                                  |
| %ME Min                        | Porcentaje de materia extraña mínima.                                       |
| %ME Veg                        | Porcentaje de materia extraña vegetal.                                      |
| %ME Tot                        | Porcentaje total de materia extraña.                                        |
| Brix                           | Concentración de sólidos solubles (°Brix).                                  |
| Pureza                         | Relación entre sacarosa y sólidos solubles.                                 |
| Vejez                          | Edad avanzada del cultivo en cosecha.                                       |
| Num.Riegos                     | Número de riegos aplicados.                                                 |
| M3 Riego                       | Volumen total de riego aplicado (m³).                                       |
| DDUlt.Riego                    | Días desde el último riego.                                                 |
| Lluvias (2 Meses Ant.)         | Precipitación acumulada 2 meses antes de la cosecha.                        |
| Lluvias Ciclo                  | Precipitación acumulada en todo el ciclo.                                   |
| Lluvias 0 -3                   | Precipitación entre 0 y 3 meses previos.                                    |
| Lluvias tres a seis            | Precipitación entre 3 y 6 meses previos.                                    |
| Lluvias seis a nueve           | Precipitación entre 6 y 9 meses previos.                                    |
| Luvias 9 -FC                   | Precipitación entre 9 meses y la fecha de corte.                            |
| %Infest.Diatrea                | Nivel de infestación por diatrea (plaga).                                   |
| Fosfato Jugo                   | Concentración de fosfatos en jugo.                                          |
| Fert.Nitrogen.                 | Fertilizante nitrogenado aplicado.                                          |
| Urea 46%                       | Cantidad de urea (46%) aplicada.                                            |
| MEZ                            | Fertilizante mezclado aplicado.                                             |
| Boro Granul.                   | Cantidad de boro aplicado en forma granular.                                |
| MicroZinc                      | Cantidad de zinc aplicado.                                                  |
| NITO_XTEND                     | Fertilizante tipo nitrógeno de liberación controlada.                       |
| Sul.Amonio                     | Sulfato de amonio aplicado.                                                 |
| NITRAX-S                       | Fertilizante nitrógeno aplicado (variante S).                               |
| Vinaza                         | Vinaza aplicada como fertilizante.                                          |
| Temp. Media 0-3                | Temperatura media en 0-3 meses previos.                                     |
| Temp. Media Ciclo              | Temperatura media durante el ciclo.                                         |
| Temp Max Ciclo                 | Temperatura máxima del ciclo.                                               |
| Temp Min Ciclo                 | Temperatura mínima del ciclo.                                               |
| Humedad Rel Media 0-3          | Humedad relativa media en 0-3 meses previos.                                |
| Humedad Rel Media Ciclo        | Humedad relativa media del ciclo.                                           |
| Oscilacion Temp Med 0-3        | Oscilación térmica en 0-3 meses previos.                                    |
| Oscilacion Temp Ciclo          | Oscilación térmica durante el ciclo.                                        |
| Sum Oscilacion Temp Ciclo      | Suma acumulada de la oscilación térmica.                                    |
| Radicion Solar 0-3             | Radiación solar acumulada en 0-3 meses previos.                             |
| Radiacion Solar Ciclo          | Radiación solar acumulada en el ciclo.                                      |
| Precipitacion 0_3              | Precipitación acumulada en 0-3 meses previos.                               |
| Precipitacion Ciclo            | Precipitación acumulada en el ciclo.                                        |
| Evaporacion 0-3                | Evaporación acumulada en 0-3 meses previos.                                 |
| Evaporacion Ciclo              | Evaporación acumulada en el ciclo.                                          |

---

## 🔹 Variables Categóricas

| Columna          | Descripción                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Nombre           | Nombre asignado a la unidad de análisis (campo, plantación o cultivo).       |
| Zona             | Región geográfica donde se ubica la hacienda o cultivo.                     |
| Suerte           | Identificador del lote específico dentro de la hacienda.                    |
| Suelo            | Tipo de suelo presente en la parcela (arenoso, arcilloso, etc.).            |
| Variedad         | Variedad del cultivo (ej. tipo de caña de azúcar).                          |
| Cod.Estado       | Estado del cultivo en formato de texto.                                     |
| D.S.             | Descripción adicional del estado.                                           |
| Cultivo          | Nombre del cultivo plantado.                                                |
| Producto         | Producto obtenido (ej. caña, azúcar, jugo).                                 |
| Tipo Quema       | Tipo de quema realizada (si aplica).                                        |
| T.Corte          | Tipo de corte aplicado.                                                     |
| Cerca de         | Proximidad a infraestructura u otra referencia.                             |
| Cosechó          | Indicador de si se cosechó (Sí/No).                                         |
| Codigo Estacion  | Código de la estación meteorológica asociada.                               |

---


3. Clasificacion -> Apartir de las variables continuas (TCH y %sac), crear categorias que permitan clasificar los registros en niveles de desempeño
    - para %sac niveles de sacarosa alto, medio y bajo
    - para TCH niveles alto, medio y bajo
    - intrucciones: Definir los umbrales de transformacion de las variables continuas
    - AJustar un modelo de regresion logistica o un knn
    - emplear una estrategia de validacion reportar metricas de evaluacion para la clasificacion
    - 


