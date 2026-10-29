desarrollo:
Conectar los periféricos, capturar la fotografía, eliminar el fondo, crear la portada y generar el QR.
arquitectura del proyecto:

Dos detalles importantes para el desarrollo:
La cuenta atrás debe activar automáticamente la captura al llegar a cero, sin que el usuario tenga que pulsar otra vez el teclado.
El QR debe generarse únicamente cuando la portada esté terminada y subida al almacenamiento online. Así, cuando el usuario lo escanee, la imagen ya estará disponible.
Programación de el teclado: 
a= izq
b= der
c= intro 


Entornos de trabajo y lenguajes:
Visual Studio Code: para escribir y organizar el código.
Python: para procesar las fotografías y generar las portadas.
Google Chrome: para ejecutar la interfaz.
Cámara Logitech: conectada por USB.
Teclado Energy Sistem: conectado por USB.

Estructura de las carpetas:
photos: pruebas iniciales para saber que la cámara funciona en el nav en local

Librerías necesarias:

Pillow es una librería de Python que permite abrir, modificar, combinar y exportar imágenes. Es para manipular imágenes que ya existen 

RemBG y ONNX Runtime: ¿cuál es la diferencia? Trabajan juntas, pero tienen funciones diferentes. 

ONNX Runtime es un motor que permite ejecutar modelos de inteligencia artificial. es el motor que ejecuta ese modelo y calcula el resultado 

qrcode es una librería de Python que permite crear códigos QR a partir de información. el QR no contiene la fotografía, sino un enlace que permite acceder a ella. 
FastAPI es una herramienta que permite crear un servidor que recibe peticiones y ejecuta funciones de Python. 

Uvicorn es un servidor web que ejecuta nuestra aplicación FastAPI. 

Nota:
Por defecto está instalada la versión 3.15 de Python, pero varias de las librerías aún no son compatibles con dicha versión, por tanto para evitar fallos vamos a hacer un env.(entorno virtual para ejecutar python con diferentes versiones)
