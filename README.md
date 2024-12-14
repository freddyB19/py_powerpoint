## Instalación y ejecución

```
1. Clona el repositorio::

        git clone https://github.com/freddyB19/py_powerpoint.git
        cd py_powerpoint

2. Crea y activa el entorno virtual::
        *Para Linux:*
        python3 -m venv venv
        source venv/bin/activate

        *Windows:*
        python -m venv venv
        venv\Scripts\activate

        (Para usuarios Windows, recomiendo consultar la documentación)

3. Instala los requerimientos::

        pip install -r requirements.txt

4. Ejecuta el Script::
                
        (Linux)   python3 main.py
        (Windows) python main.py
```

En la carpeta <ins>file</ins> dentro del proyecto se encuentra el archivo **trial.pptx**
el cual tiene en su contenido el texto *"Hola"* (puedes verificar esto abriendo el archivo).
Al ejecutar el script el texto del archivo cambia por: *"Gracias"*

