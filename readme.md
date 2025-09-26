# AWS Life Number App ✨  

Aplicación desarrollada para el **stand de AWS en Nerdearla**, que combina tecnologías en la nube con un pequeño toque místico: a partir de tu **fecha de nacimiento**, la app calcula un **Número de Vida** y comparte ideas asociadas a ese número.  

---

### 🚀 Descripción  

La aplicación recibe como entrada la fecha de nacimiento de una persona, procesa los datos y devuelve:  

- Un **Número de Vida** único, calculado mediante un algoritmo simple de reducción numerológica.  
- Una serie de **ideas y frases inspiradoras** asociadas al número obtenido.  

El objetivo es ofrecer una experiencia interactiva, divertida y memorable dentro del evento, mostrando la versatilidad de las herramientas de **Amazon Web Services (AWS)** en tiempo real.  

---

### 🛠️ Tecnologías Utilizadas  

Este proyecto se construyó aprovechando diversos servicios de AWS:  

- **AWS Lambda** → Lógica sin servidor para el cálculo del número de vida.  
- **Amazon API Gateway** → Creación y exposición de la API para la app.  
- **Amazon DynamoDB** → Almacenamiento de la base de datos con las ideas asociadas a cada número.  
- **Amazon S3** → Hosting de la aplicación frontend estática.  
- **AWS Amplify** (opcional) → Para integrar y desplegar fácilmente la app. 

---

### 🧮 Ejemplo de Uso  

1. El usuario ingresa su fecha de nacimiento (ejemplo: 21/07/1993).  
2. La aplicación suma los dígitos: 2+1+0+7+1+9+9+3 = 32 → 3+2 = **5**.  
3. El resultado mostrado será:  
   - Tu Número de Vida: **5**  
   - Ideas asociadas: *Libertad, aventura, adaptación, curiosidad.*  

---

### 🎯 Objetivo del Proyecto  

- Mostrar de manera simple cómo AWS permite crear aplicaciones **serverless, rápidas y escalables**.  
- Generar interacción divertida y personalizada con el público del stand.  
- Inspirar a experimentar con **cloud computing** en proyectos 
