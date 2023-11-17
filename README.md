## Paso1: Redirigete a la carpeta del proyecto

## Paso2: Cree el ambiente virtual
python -m venv mienv

## Paso3: Activar el entorno virtual
myenv\Scripts\activate

### Observación: si está en MacOs o Linux debe usar:
source myenv/bin/activate

## Paso4: Instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso 5: Luego descargar el csv más reciente de la sgte url
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: Ejecutar la aplicación
python get_excel_resumen_es.py