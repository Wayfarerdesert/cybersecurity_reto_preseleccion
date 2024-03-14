# Cyberskilling Hackathon

### Informe de Auditoría


## Introducción
Este informe presenta los hallazgos y recomendaciones resultantes de la evaluación realizada durante la competencia de Capture The Flag. El objetivo principal de esta auditoría fue identificar posibles vulnerabilidades en la infraestructura de la aplicación web proporcionada y sugerir medidas de mitigación adecuadas.

## Descripción del Alcance
El alcance de la auditoría se centró en la evaluación de la seguridad de la presencia web de la empresa simulada, proporcionada en forma de una máquina virtual (VM) para la competencia. El equipo realizo diversas pruebas y ataques, incluyendo inyección SQL, reinicio de contraseña, exploración de directorios, y más.


## Hallazgos
Durante la competencia, se identificaron varias vulnerabilidades significativas, que incluyen:
- Una vulnerabilidad de inyección SQL en la aplicación web.
- Falta de seguridad en el acceso al modo de recuperación.
- Exposición de información sensible.
- Acceso no restringido a archivos y directorios.

## Recomendaciones
Para mitigar estos riesgos, se sugieren las siguientes acciones:
- Implementar la validación de entradas y la sanitización de datos en la aplicación web.
- Reforzar las políticas de contraseñas y gestionar el acceso al modo de recuperación en la BIOS.
- Restringir el acceso a archivos sensibles mediante permisos adecuados.
- Considerar la implementación de autenticación de dos factores (2FA) para aumentar la seguridad del sistema.


## Documento Completo
Para acceder al informe completo, por favor visita el siguiente enlace: [Informe Completo](CyberGuardians.pdf)
