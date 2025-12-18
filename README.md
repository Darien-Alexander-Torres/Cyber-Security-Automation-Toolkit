# Cyber Security Automation Toolkit 🛡️

Este repositorio contiene una suite integral de **14 herramientas** de ciberseguridad desarrolladas en **Python, PowerShell y Bash**. El sistema está diseñado para ser multiplataforma, detectando automáticamente el sistema operativo (Windows, Linux o MacOS) para desplegar los módulos compatibles.

# 🚀 Arquitectura del Sistema
El proyecto utiliza un orquestador principal (`4E-Main.py`) que gestiona la ejecución de los módulos mediante submódulos de integración (`pspy.py`, `pypy.py`, `shpy.py`).

# 🛠️ Módulos de Operaciones de Seguridad (SecOps)

# 🐍 Python (Amenazas y Criptografía)
* Threat Intelligence: Integración con APIs de **Shodan, AbuseIPDB e InternetDB** para análisis de vulnerabilidades y reputación de IPs.
* File Encryptor: Módulo de criptografía simétrica (Fernet) para el cifrado seguro de archivos con manejo de logs.
* Port Scanner: Escáner basado en sockets para la detección de servicios activos.

#📜 PowerShell (Forense y Monitoreo Windows)
* LoginLogs: Auditoría de logs de seguridad de Windows (Event IDs 4624, 4625) para detectar intrusiones.
* VirusTotal Integrator: Cálculo de hashes SHA256 y consulta automatizada a la API de VirusTotal.
* Resources & Hidden Files: Herramientas para el monitoreo de salud del sistema y descubrimiento de archivos ocultos.

#🐧 Bash (Defensa Activa Linux)
* PortScan & Honeypot: Implementación de reconocimiento de red y sistemas trampa para la detección temprana de amenazas.

#🔒 Garantía de Integridad
Para asegurar la validez de los resultados en un entorno profesional de **CDC**, el sistema genera automáticamente un **hash SHA-512** de cada reporte técnico generado, garantizando que la evidencia no ha sido alterada.

#👥 Créditos
Proyecto desarrollado como parte de la formación en LSTI (UANL).
* Darien T.
* Chris T.
* Santiago B.
