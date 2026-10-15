# TP1
TRABAJO PRACTICO 1

OBJETIVO DEL TRABAJO:
El objetivo principal, y por el cual yo elegí este Dataset, es poder entender qué factores parecen estar asociados al riesgo de diabetes y poder descubrir patrones que permitieran explicar el comportamiento del riesgo de diabetes en la población estudiada.

CONTEXTO DEL DATASET:
Este dataset se obtuvo desde la página web de kaggle y fue construido para simular o evaluar el riesgo de diabetes a partir de múltiples factores clínicos, antropométricos, hábitos de vida y antecedentes médicos.
El conjunto de datos combina información demográfica, medidas corporales, resultados de pruebas de laboratorio, indicadores cardiovasculares, hábitos de estilo de vida, antecedentes médicos familiares entre otros.
Está destinado a fines educativos, a la investigación y al desarrollo de modelos predictivos en el ámbito sanitario.

DICCIONARIO DE DATOS:
Identificación del Paciente<br>
1.	Patient_ID - Tipo: Numérico (entero)<br>
    •	Descripción: Identificador único asignado a cada paciente.<br>

Datos Demográficos<br>
2.	Age - Tipo: Numérico<br>
    •	Descripción: Edad del paciente en años.
3.	Gender - Tipo: Categórico<br>
    •	Valores posibles: Male, Female, Other<br>
    •	Descripción: Género del paciente.<br>
4.	Country - Tipo: Texto<br>
    •	Descripción: País de residencia del paciente.<br>

Medidas Antropométricas<br>
5.	Height_cm - Tipo: Numérico<br>
    •	Unidad: centímetros (cm)<br>
    •	Descripción: Altura del paciente.<br>
6.	Weight_kg - Tipo: Numérico<br>
    •	Unidad: kilogramos (kg)<br>
    •	Descripción: Peso corporal.<br>
7.	BMI - Tipo: Numérico<br>
    •	Unidad: kg/m²<br>
    •	Descripción: Índice de Masa Corporal.<br>
8.	WaistCircumferencecm - Tipo: Numérico<br>
    •	Unidad: centímetros (cm)<br>
    •	Descripción: Circunferencia de cintura.<br>

Indicadores Glucémicos - Blood_Glucose<br>
    •	Tipo: Numérico<br>
    •	Unidad: mg/dL<br>
    •	Descripción: Nivel de glucosa en sangre.<br>
10.	HbA1c - Tipo: Numérico<br>
    •	Unidad: %<br>
    •	Descripción: Hemoglobina glucosilada, refleja el promedio de glucosa de los últimos 2-3 meses.<br>
11.	FastingBloodSugar - Tipo: Numérico<br>
    •	Unidad: mg/dL<br>
    •	Descripción: Glucemia en ayunas.<br>
12.	Insulin_Level - Tipo: Numérico<br>
    •	Unidad: μU/mL<br>
    •	Descripción: Nivel de insulina en sangre.<br>

Presión Arterial<br>
13.	BloodPressureSystolic - Tipo: Numérico<br>
    •	Unidad: mmHg<br>
    •	Descripción: Presión arterial sistólica.<br>
14.	BloodPressureDiastolic - Tipo: Numérico<br>
    •	Unidad: mmHg<br>
    •	Descripción: Presión arterial diastólica.<br>

Perfil Lipídico - Total_Cholesterol<br>
    •	Tipo: Numérico<br>
    •	Unidad: mg/dL<br>
    •	Descripción: Colesterol total.<br>
16.	HDL - Tipo: Numérico<br>
    •	Unidad: mg/dL<br>
    •	Descripción: Colesterol HDL ("colesterol bueno").<br>
17.	LDL - Tipo: Numérico<br>
    •	Unidad: mg/dL<br>
    •	Descripción: Colesterol LDL ("colesterol malo").<br>
18.	Triglycerides - Tipo: Numérico<br>
    •	Unidad: mg/dL<br>
    •	Descripción: Nivel de triglicéridos.<br>

Indicadores Fisiológicos<br>
19.	Heart_Rate - Tipo: Numérico<br>
    •	Unidad: latidos por minuto (bpm)<br>
    •	Descripción: Frecuencia cardíaca.<br>

Actividad Física<br>
20.	PhysicalActivityLevel - Tipo: Categórico<br>
    •	Valores posibles: Low, Moderate, High<br>
    •	Descripción: Nivel general de actividad física.<br>
21.	ExerciseHoursPer_Week - Tipo: Numérico<br>
    •	Unidad: horas por semana<br>
    •	Descripción: Tiempo destinado al ejercicio físico semanal.<br>
22.	DailyWalkingMinutes - Tipo: Numérico<br>
    •	Unidad: minutos por día<br>
    •	Descripción: Minutos caminados diariamente.<br>

Hábitos Alimenticios<br>
23.	Diet_Quality - Tipo: Categórico<br>
    •	Valores posibles: Healthy, Average, Poor<br>
    •	Descripción: Calidad general de la alimentación.<br>
24.	SugarIntakeLevel - Tipo: Categórico<br>
    •	Valores posibles: Low, Moderate, High<br>
    •	Descripción: Nivel de consumo de azúcar.<br>

Estilo de Vida<br>
25.	Sleep_Hours - Tipo: Numérico<br>
    •	Unidad: horas por día<br>
    •	Descripción: Cantidad promedio de horas de sueño.<br>
26.	Stress_Level - Tipo: Categórico<br>
    •	Valores posibles: Low, Moderate, High<br>
    •	Descripción: Nivel percibido de estrés.<br>
27.	Smoking_Status - Tipo: Categórico<br>
    •	Valores posibles: Never, Former, Current<br>
    •	Descripción: Estado de tabaquismo.<br>
28.	Alcohol_Consumption - Tipo: Categórico<br>
    •	Valores posibles: Never, Occasionally, Frequently<br>
    •	Descripción: Frecuencia de consumo de alcohol.<br>
29.	DailyWaterIntake_L - Tipo: Numérico<br>
    •	Unidad: litros por día<br>
    •	Descripción: Consumo diario de agua.<br>

Antecedentes Médicos<br>
30.	FamilyHistoryDiabetes - Tipo: Categórico<br>
    •	Valores posibles: Yes, No<br>
    •	Descripción: Antecedentes familiares de diabetes.<br>
31.	Hypertension - Tipo: Categórico<br>
    •	Valores posibles: Yes, No<br>
    •	Descripción: Presencia de hipertensión arterial.<br>
32.	Heart_Disease - Tipo: Categórico<br>
    •	Valores posibles: Yes, No<br>
    •	Descripción: Antecedentes de enfermedad cardíaca.<br>
33.	Fatty_Liver - Tipo: Categórico<br>
    •	Valores posibles: Yes, No<br>
    •	Descripción: Presencia de hígado graso.<br>
34.	PCOS - Tipo: Categórico<br>
    •	Valores posibles: Yes, No<br>
    •	Descripción: Síndrome de ovario poliquístico.<br>
35.	Medication_Adherence - Tipo: Categórico<br>
    •	Valores posibles: Good, Average, Poor<br>
    •	Descripción: Nivel de adherencia a tratamientos médicos.<br>

Variables Socioeconómicas<br>
36.	Work_Type - Tipo: Categórico<br>
    •	Valores posibles: Government, Private, Business, Student, Retired<br>
    •	Descripción: Tipo de ocupación o actividad laboral.<br>
37.	Residence_Type - Tipo: Categórico<br>
    •	Valores posibles: Urban, Rural<br>
    •	Descripción: Lugar de residencia.<br>

Variables Objetivo<br>
38.	DiabetesRiskScore - Tipo: Numérico<br>
    •	Rango aproximado: 0 - 100<br>
    •	Descripción: Puntaje de riesgo de diabetes calculado a partir de múltiples variables.<br>
39.	AIHealthRecommendation - Tipo: Texto<br>
    •	Descripción: Recomendación generada por un sistema de IA en función del perfil de riesgo.<br>
40.	DoctorConsultationNeeded - Tipo: Categórico<br>
    •	Valores posibles: Yes, No<br>
    •	Descripción: Indica si se recomienda consulta médica.<br>
41.	Diabetes_Risk - Tipo: Categórico<br>
    •	Valores posibles: Low, Moderate, High<br>
    •	Descripción: Clasificación final del riesgo de diabetes.<br>

METODOLOGÍA APLICADA:<br>
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

CONCLUSIONES Y HALLAZGOS RELEVANTES:<br>
La diabetes es una enfermedad multifactorial, por ese motivo no alcanza con observar 1 única variable, pero si bien la Obesidad es uno de los factores mas asociados con el riesgo alto de Diabetes, no podemos dejar fuera variables como los Antecedentes Familiares o la Edad

El hallazgo más valioso del análisis fue detectar que, ademas de los factores tradicionales, la presencia de Antecedentes Familiares puede asociarse a niveles elevados de riesgo, incluso en individuos jóvenes y con IMC normal, sugiriendo que los factores genéticos podrían desempeñar un papel muy importante y asi, romper con la teoría de que el mayor riesgo lo poseen las personas obesas.

