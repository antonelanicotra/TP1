# TP1
TRABAJO PRACTICO 1

OBJETIVO DEL TRABAJO:
El objetivo principal, y por el cual yo elegí este Dataset, es poder entender qué factores parecen estar asociados al riesgo de diabetes y poder descubrir patrones que permitieran explicar el comportamiento del riesgo de diabetes en la población estudiada.

CONTEXTO DEL DATASET:
Este dataset se obtuvo desde la página web de kaggle y fue construido para simular o evaluar el riesgo de diabetes a partir de múltiples factores clínicos, antropométricos, hábitos de vida y antecedentes médicos.
El conjunto de datos combina información demográfica, medidas corporales, resultados de pruebas de laboratorio, indicadores cardiovasculares, hábitos de estilo de vida, antecedentes médicos familiares entre otros.
Está destinado a fines educativos, a la investigación y al desarrollo de modelos predictivos en el ámbito sanitario.

DICCIONARIO DE DATOS:
Identificación del Paciente
1.	Patient_ID - Tipo: Numérico (entero)
    •	Descripción: Identificador único asignado a cada paciente.

Datos Demográficos
2.	Age - Tipo: Numérico
    •	Descripción: Edad del paciente en años.
3.	Gender - Tipo: Categórico
    •	Valores posibles: Male, Female, Other
    •	Descripción: Género del paciente.
4.	Country - Tipo: Texto
    •	Descripción: País de residencia del paciente.

Medidas Antropométricas
5.	Height_cm - Tipo: Numérico
    •	Unidad: centímetros (cm)
    •	Descripción: Altura del paciente.
6.	Weight_kg - Tipo: Numérico
    •	Unidad: kilogramos (kg)
    •	Descripción: Peso corporal.
7.	BMI - Tipo: Numérico
    •	Unidad: kg/m²
    •	Descripción: Índice de Masa Corporal.
8.	WaistCircumferencecm - Tipo: Numérico
    •	Unidad: centímetros (cm)
    •	Descripción: Circunferencia de cintura.

Indicadores Glucémicos - Blood_Glucose
    •	Tipo: Numérico
    •	Unidad: mg/dL
    •	Descripción: Nivel de glucosa en sangre.
10.	HbA1c - Tipo: Numérico
    •	Unidad: %
    •	Descripción: Hemoglobina glucosilada, refleja el promedio de glucosa de los últimos 2-3 meses.
11.	FastingBloodSugar - Tipo: Numérico
    •	Unidad: mg/dL
    •	Descripción: Glucemia en ayunas.
12.	Insulin_Level - Tipo: Numérico
    •	Unidad: μU/mL
    •	Descripción: Nivel de insulina en sangre.

Presión Arterial
13.	BloodPressureSystolic - Tipo: Numérico
    •	Unidad: mmHg
    •	Descripción: Presión arterial sistólica.
14.	BloodPressureDiastolic - Tipo: Numérico
    •	Unidad: mmHg
    •	Descripción: Presión arterial diastólica.

Perfil Lipídico - Total_Cholesterol
    •	Tipo: Numérico
    •	Unidad: mg/dL
    •	Descripción: Colesterol total.
16.	HDL - Tipo: Numérico
    •	Unidad: mg/dL
    •	Descripción: Colesterol HDL ("colesterol bueno").
17.	LDL - Tipo: Numérico
    •	Unidad: mg/dL
    •	Descripción: Colesterol LDL ("colesterol malo").
18.	Triglycerides - Tipo: Numérico
    •	Unidad: mg/dL
    •	Descripción: Nivel de triglicéridos.

Indicadores Fisiológicos
19.	Heart_Rate - Tipo: Numérico
    •	Unidad: latidos por minuto (bpm)
    •	Descripción: Frecuencia cardíaca.

Actividad Física
20.	PhysicalActivityLevel - Tipo: Categórico
    •	Valores posibles: Low, Moderate, High
    •	Descripción: Nivel general de actividad física.
21.	ExerciseHoursPer_Week - Tipo: Numérico
    •	Unidad: horas por semana
    •	Descripción: Tiempo destinado al ejercicio físico semanal.
22.	DailyWalkingMinutes - Tipo: Numérico
    •	Unidad: minutos por día
    •	Descripción: Minutos caminados diariamente.

Hábitos Alimenticios
23.	Diet_Quality - Tipo: Categórico
    •	Valores posibles: Healthy, Average, Poor
    •	Descripción: Calidad general de la alimentación.
24.	SugarIntakeLevel - Tipo: Categórico
    •	Valores posibles: Low, Moderate, High
    •	Descripción: Nivel de consumo de azúcar.

Estilo de Vida
25.	Sleep_Hours - Tipo: Numérico
    •	Unidad: horas por día
    •	Descripción: Cantidad promedio de horas de sueño.
26.	Stress_Level - Tipo: Categórico
    •	Valores posibles: Low, Moderate, High
    •	Descripción: Nivel percibido de estrés.
27.	Smoking_Status - Tipo: Categórico
    •	Valores posibles: Never, Former, Current
    •	Descripción: Estado de tabaquismo.
28.	Alcohol_Consumption - Tipo: Categórico
    •	Valores posibles: Never, Occasionally, Frequently
    •	Descripción: Frecuencia de consumo de alcohol.
29.	DailyWaterIntake_L - Tipo: Numérico
    •	Unidad: litros por día
    •	Descripción: Consumo diario de agua.

Antecedentes Médicos
30.	FamilyHistoryDiabetes - Tipo: Categórico
    •	Valores posibles: Yes, No
    •	Descripción: Antecedentes familiares de diabetes.
31.	Hypertension - Tipo: Categórico
    •	Valores posibles: Yes, No
    •	Descripción: Presencia de hipertensión arterial.
32.	Heart_Disease - Tipo: Categórico
    •	Valores posibles: Yes, No
    •	Descripción: Antecedentes de enfermedad cardíaca.
33.	Fatty_Liver - Tipo: Categórico
    •	Valores posibles: Yes, No
    •	Descripción: Presencia de hígado graso.
34.	PCOS - Tipo: Categórico
    •	Valores posibles: Yes, No
    •	Descripción: Síndrome de ovario poliquístico.
35.	Medication_Adherence - Tipo: Categórico
    •	Valores posibles: Good, Average, Poor
    •	Descripción: Nivel de adherencia a tratamientos médicos.

Variables Socioeconómicas
36.	Work_Type - Tipo: Categórico
    •	Valores posibles: Government, Private, Business, Student, Retired
    •	Descripción: Tipo de ocupación o actividad laboral.
37.	Residence_Type - Tipo: Categórico
    •	Valores posibles: Urban, Rural
    •	Descripción: Lugar de residencia.

Variables Objetivo
38.	DiabetesRiskScore - Tipo: Numérico
    •	Rango aproximado: 0 - 100
    •	Descripción: Puntaje de riesgo de diabetes calculado a partir de múltiples variables.
39.	AIHealthRecommendation - Tipo: Texto
    •	Descripción: Recomendación generada por un sistema de IA en función del perfil de riesgo.
40.	DoctorConsultationNeeded - Tipo: Categórico
    •	Valores posibles: Yes, No
    •	Descripción: Indica si se recomienda consulta médica.
41.	Diabetes_Risk - Tipo: Categórico
    •	Valores posibles: Low, Moderate, High
    •	Descripción: Clasificación final del riesgo de diabetes.

METODOLOGÍA APLICADA:
Con el objetico de explorar los factores asociados al riesgo de diabetes e identificar patrones, tendencias y segmentos poblacionales relevantes se utilizó la siguiente metodología:
1.	Comprensión de los datos, se revisó el dataset para:
    •	Identificar y Clasificar variables.
    •	Detectar valores nulos.
    •	Verificar tipos de datos.
    •	Comprender el significado de cada atributo.
    Con esto se detectaron las siguientes variables de Interés:
    •	Edad (Age)
    •	IMC (BMI)
    •	Circunferencia de cintura (WaistCircumferencecm)
    •	Horas de sueño (Sleep_Hours)
    •	Antecedentes familiares (FamilyHistoryDiabetes)
    •	Riesgo de diabetes (Diabetes_Risk)

2.	 Análisis descriptivo, para poder encontrar la variable objetivo sobre la cual trabajar, se calcularon:
    •	Media
    •	Mediana
    •	Desviación estándar
    •	Mínimo y máximo
    •	Cuartiles

3.	Formular hipótesis, con los patrones observados se formulan las siguientes hipótesis:
    •	H1: Los pacientes con obesidad presentan un riesgo de diabetes elevado.
    •	H2: Una mayor circunferencia de cintura aumenta el riesgo de diabetes.
    •	H3: Los individuos con antecedentes familiares tienen mayor probabilidad de presentar riesgo elevado.
    •	H4: La falta de sueño se asocia con mayores niveles de riesgo.
    •	H5: La probabilidad de riesgo alto aumenta con la edad.

4.	Se segmentó a la población creando grupos específicos con el objetivo de analizar perfiles concretos y detectar diferentes comportamientos
    •	Grupo de ICM + Riesgo de Diebetes
        o	G0 Bajo Peso, Alto Riesgo
        o	G1 Peso Normal, Alto Riesgo
        o	G2 Peso Normal, Riesgo Normal
        o	G3 Sobrepeso, Alto Riesgo
    •	Grupo Obesidad, en base a si el ICM es >=25:
        o	Obeso
        o	No Obeso
    •	Grupo Cintura + Riesgo
        o	GC0 Cintura Chica, Alto Riesgo
        o	GC1 Cintura Normal, Alto Riesgo
        o	GC2 Cintura Normal, Riesgo Normal
        o	GC3 Cintura Grande, Alto Riesgo
    •	Grupo Sueño:
        o	Poco Sueño (< 6 horas)
        o	Sueño Normal (6-8 horas) 
        o	Mucho Sueño (> 8 horas)
    •	Grupo Edad:
        o	Jovenes <30
        o	Adultos Jóvenes 30-45
        o	Adultos 45-60
        o	Adultos Mayores >60

5.	Análisis visual, para poder generar conclusiones se analizaron los siguientes gráficos:
    •	Histogramas con y sin KDE
    •	Boxplots
    •	ScatterPlots
    •	Barras
    •	Lineas
    •	Torta

6.	Se buscan segmentos atípicos, para poder presentar in Insight interesante desde la perspectiva médica, se pensaron combinaciones inesperadas

CONCLUSIONES Y HALLAZGOS RELEVANTES:
La diabetes es una enfermedad multifactorial, por ese motivo no alcanza con observar 1 única variable, pero si bien la Obesidad es uno de los factores mas asociados con el riesgo alto de Diabetes, no podemos dejar fuera variables como los Antecedentes Familiares o la Edad

El hallazgo más valioso del análisis fue detectar que, ademas de los factores tradicionales, la presencia de Antecedentes Familiares puede asociarse a niveles elevados de riesgo, incluso en individuos jóvenes y con IMC normal, sugiriendo que los factores genéticos podrían desempeñar un papel muy importante y asi, romper con la teoría de que el mayor riesgo lo poseen las personas obesas.

