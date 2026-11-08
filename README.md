# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- Nombre completo: Wilber Eduardo Orellana
- Carné: N/P
- Correo institucional: edd.orellana7@gmail.com
- Asignatura: Lenguajes de Programacion con Aspectos de Seguridad
- Fecha: 07 de noviembre de 2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
Laboratorio-las/
├── templates/
│   ├── login.html
│   └── registro.html
├── app.py
├── crearDB.py
├── detector.py
├── eventos.log
├── requirements.txt
├── respuesta.log
├── usuarios.db
└── README.md
```

## 4. Métricas de Incidentes (Resultados de Pruebas)

Durante la fase de pruebas del sistema de detección y respuesta, se obtuvieron las siguientes métricas promedio:

MTTD Promedio: 12.0 segundos
MTTR Promedio: 466.67 segundos
