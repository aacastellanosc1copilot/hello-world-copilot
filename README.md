# Aplicación Hola Mundo Copilot

Instrucciones:

1. Crear entorno virtual (recomendado):
   python3 -m venv .venv
   source .venv/bin/activate

2. Instalar dependencias:
   pip install -r requirements.txt

3. Ejecutar la aplicación:
   uvicorn main:app --reload

4. Abrir en el navegador:
   http://127.0.0.1:8000/

La aplicación usa SQLite en sqlite:///./app.db con connect_args={'check_same_thread': False}.