# usa imagen de python
FROM python:3.9-slim

#crea directorio de trabajo
WORKDIR /app

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

#expone el puerto 5000
EXPOSE 5000

#ejecutar la aplicacion
CMD ["python", "app.py"]