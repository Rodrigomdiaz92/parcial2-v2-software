# Control de Stock - Parcial 2 (Ingeniería de Software)

- **Alumno:** Rodrigo Martín Díaz
- **Fecha:** 18/11/2026

## Instrucciones Docker

Construir la imagen:
```bash
docker build -t parcial2-software .
```
Ejecutar el contenedor:
```bash
docker run -d -p 8080:80 --name app-parcial2 parcial2-software
```
Acceder en el navegador: http://localhost:8080