<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# EmoTrack: Asistente de IA para el bienestar emocional

Final project for the Building AI course

## Summary

EmoTrack es una herramienta basada en IA que analiza mensajes escritos (como diarios personales o chats) para detectar emociones y ofrecer recomendaciones personalizadas para mejorar el bienestar emocional. Ayuda a los usuarios a reflexionar sobre su estado emocional y tomar decisiones más conscientes. 


## Background

La salud mental es un tema crítico y cada vez más presente en nuestras vidas. Muchas personas experimentan ansiedad, estrés o depresión sin darse cuenta de cómo evolucionan sus emociones a lo largo del tiempo. EmoTrack busca ayudar a los usuarios a identificar patrones emocionales y recibir sugerencias útiles.

Problemas que aborda:
* Dificultad para identificar y expresar emociones
* Falta de seguimiento del estado emocional diario
* Necesidad de herramientas accesibles para el autocuidado mental
Mi motivación personal surge del interés por combinar tecnología y bienestar humano. Este proyecto puede ser una herramienta valiosa para quienes buscan mejorar su salud emocional sin recurrir directamente a terapia profesional.


## How is it used?

El usuario escribe libremente sobre su día, sus pensamientos o sentimientos. EmoTrack analiza el texto y devuelve:
* Un resumen emocional (por ejemplo: "Predominan emociones de tristeza y ansiedad")
* Recomendaciones personalizadas (ejercicios de respiración, journaling, contacto social)
* Un gráfico de evolución emocional si se usa de forma continua
Usuarios:
* Personas interesadas en el autocuidado emocional
* Estudiantes, trabajadores, cuidadores
* Profesionales que desean monitorear su bienestar
Se puede usar en una app móvil, una extensión de navegador o una plataforma web.


<img width="423" height="277" alt="image" src="https://github.com/user-attachments/assets/a51713fa-f9a1-4e02-bd8c-56923611b2a7" />



## Data sources and AI methods
Fuentes de datos:
* Dataset de emociones en texto como Emotion Dataset from Kaggle. (https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
* Datos generados por los propios usuarios (con consentimiento)

Técnicas de IA:
* Procesamiento de lenguaje natural (NLP)
* Modelos de clasificación de emociones (como BERT o DistilBERT)
* Visualización de datos con bibliotecas como Matplotlib o Plotly

## Challenges

Limitaciones:
* No reemplaza la terapia profesional
*Puede haber errores en la interpretación emocional
* Riesgos éticos si se usa sin consentimiento o sin privacidad adecuada

Consideraciones éticas:
* Protección de datos personales
* Transparencia en el uso de modelos
* Evitar recomendaciones que puedan causar daño

## What next?

Futuras mejoras:
* Integración con dispositivos de bienestar (como pulseras inteligentes)
* Soporte multilingüe
* Incorporación de análisis de voz y expresión facial

Para avanzar, se necesitaría:
* Colaboración con psicólogos
* Validación clínica
* Financiamiento para desarrollo de app

## Acknowledgments

Inspirado por el curso Building AI de Reaktor y la Universidad de Helsinki
* Dataset de emociones de Kaggle por Praveen Govi
* Modelo de emociones de Hugging Face por Jan Hartmann
* Licencias de código abierto respetadas según CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/) 
