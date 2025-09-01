# Generador-de-Partidas-Texas-Hold-em
Motor de evaluación de manos de póker
# Generador de Partidas de Póker Texas Hold'em

Este programa genera partidas simuladas de **Póker Texas Hold'em (Golden Texas)** y exporta los resultados en archivos **CSV** para su posterior análisis.  
El objetivo es proporcionar datasets de ejemplo que muestren la distribución de jugadas y permitan estudiar la probabilidad de ocurrencia de cada mano.

---

## 📦 Contenido

El archivo comprimido (`GPV1.13.rar`) incluye un carpeta GPV1.13:

- `GPV1.13.exe` → aplicación lista para ejecutar en Windows.  
- `Manual_Usuario_PokerGenerator.docx` → Breve guia de uso(sin finalizar). 
- `Muesta_Generar_Partidas.ipynb` → Cuaderno de muestra para  trabajar con los csv.  
- files →carpeta en donde se encuentran archivos de la aplicacion.
- ejemplo_resultado → carpeta en donde se encuentra un ejemplo del resultado tras ejecutar la aplicacion.
---

## 🚀 Uso

1. Descarga y descomprime el archivo `PokerGenerator.rar`.  
2. Ejecuta **GPV1.13**.  
3. El programa generará automáticamente datasets en formato `.csv` dentro de la carpeta `files/`.  
4. Cada archivo contiene partidas simuladas con las siguientes columnas principales:
   - `c1..c7` → valores de las cartas.  
   - `p1..p7` → palos de las cartas.  
   - `literales` → clasificación de la jugada.  
   - `ganador` → indica si la mano ganó en la partida.

---

## 📊 Ejemplo de análisis

El archivo Muesta_Generar_Partidas.ipynb es un notebooks de este repositorio encontrarás un **notebook de Google Colab** con ejemplos de análisis de los CSV generados.  
Podrás ver estadísticas como:

- Distribución de jugadas (Pareja, Trío, Full, Escalera Real, etc.).  
- Probabilidad de victoria por tipo de mano.  
- Rareza de Escaleras Reales.  

---

## ⚙️ Requisitos

- Sistema operativo: **Windows 10 o superior**.  
- Requiere instalación ni dependencias adicionales, anexas en requirements.txt  

## Links de interes:
- https://www.python.org/downloads/ 
- https://colab.research.google.com/
---

## ℹ️ Notas

- El programa no implementa estrategias de juego, simplemente genera partidas aleatorias.  
- Los datos son ideales para practicar análisis estadístico, pero **no deben usarse como simulaciones de póker real con apuestas**.  

---

## 📜 Licencia

Este proyecto se distribuye bajo licencia **MIT**.  
Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## ✨ Autor

Desarrollado por sebas-souto 
Contribuciones, sugerencias o reportes de errores son bienvenidos en la sección de *Issues*.
