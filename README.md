# Curso de pygames


## Comandos django
1. Crear entorno virtual
```  
  python3 -m venv ./venv
```
   
2.  Activar el entorno virtual
```
    venv\Scripts\activate # windows
    source venv/bin/activate # macOS/Linux:
```

3. Generar archivo requirements.txt, si no lo tenemos o queremos actualizarlo
```   
  pip freeze > requirements.txt
```  
   
4. Install requirements 
```   
  pip install -r requirements.txt
```

## Librerias

1. Pygame
["Documentación"](https://pypi.org/project/pygame/)

2. Pygbag
["Documentación"](https://pypi.org/project/pygbag/)


## Tutoriales o Guias

1. Running PyGame in the web browser with Pygbag
["Video"](https://youtu.be/q25i2CCNvis?si=oBWjxkGpXBr865m8)
["Repositorio"](https://github.com/educ8s/Python-Retro-Snake-Game-Pygame)


Pygame no puede ejecutarse directamente en el navegador, por lo tanto, se requiere 
instalar Pygbag para compilar el código de Python y hacer que Pygame funcione en la web. 
Pygbag genera archivos en WebAssembly para ejecutar el juego en el navegador.

- Instalación de pygbag
```
    pip install pygbag
```

- Instalación de pygame
```
    pip install pygame
```

### Generar archivos con pygbag
1. Acceder al directorio de los archivos
```
cd "mi ruta"
```
2. Generar build del proyecto, tambien inica un servidor en el puerto 8000
```
pygbag main.py
```
