# HatApi

API desarrollada con FastAPI

## Configuración del entorno

1. Crear el entorno virtual:
```bash
python3 -m venv venv
```

2. Activar el entorno virtual:
```bash
# En macOS/Linux
source venv/bin/activate

# En Windows
venv\Scripts\activate
```

3. Instalar las dependencias:
```bash
pip install -r requirements.txt
```

## Ejecutar la aplicación

```bash
uvicorn app.main:app --reload
```

La API estará disponible en: http://localhost:8000

Documentación interactiva: http://localhost:8000/docs
