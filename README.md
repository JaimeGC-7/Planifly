Planifly - Sistema de Gestión de Itinerarios
Este proyecto ha sido desarrollado como parte del curso de Calidad de Software, utilizando un enfoque de desarrollo ágil y despliegue continuo mediante FlutterFlow.

Acceso a la Aplicación:
Para revisar la funcionalidad de la aplicación y validar los requisitos de calidad implementados se puede acceder al siguiente enlace de una versión estable pero aun no completa:

https://app.flutterflow.io/run/MPB5mcTo0pcTELB8yBhv

Stack Tecnológico utilizado:
Frontend: FlutterFlow (Flutter SDK).

Backend & DB: Firebase Firestore.

Autenticación: Firebase Auth.

Calidad y Seguridad (DevSecOps)
La versión disponible en el enlace superior incluye las siguientes mejoras críticas de calidad documentadas en el informe:

Validación de Datos: Gestión de estados nulos para garantizar estabilidad de la interfaz (0 pantallas rojas).

Seguridad de Datos: Reglas de acceso en Firebase basadas estrictamente en el UID del usuario autenticado.

Rendimiento: Índices compuestos habilitados en Firestore para consultas optimizadas de itinerarios.
