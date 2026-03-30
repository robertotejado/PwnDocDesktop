# 🛡️ PwnDoc Desktop v1.0

### *La navaja suiza para Auditores Red Team y Pentesters*

**PwnDoc Desktop** es una herramienta integral de gestión de auditorías de ciberseguridad y generación automatizada de reportes técnicos y ejecutivos. Diseñada para maximizar la velocidad del auditor sin sacrificar la calidad ni la seguridad operativa (**OPSEC**).

-----
<img width="1905" height="1007" alt="PwnDocDesktop" src="https://github.com/user-attachments/assets/71396f3d-29e6-4562-9220-d226f63cbaf7" />

-----

## 🚀 Características Principales

### 🧠 Inteligencia Artificial Quirúrgica

  * **Cerebro C-Level:** Generador automático de **Resúmenes Ejecutivos** traduciendo vulnerabilidades técnicas a impacto de negocio real.
  * **Auto-Redacción Técnica:** Cazador de teorías y soluciones basado en la API de Gemini para autocompletar hallazgos en segundos.
  * **Modo Formal:** La IA escribe estrictamente en segunda persona formal (*Usted/Ustedes*), lista para entregar al cliente.

### 📚 Arsenal de Plantillas Local (Offline)

  * Guarda tus descripciones perfectas para vulnerabilidades frecuentes (SMB, SSL, Inyecciones).
  * Carga tu arsenal al instante sin depender de internet ni de APIs externas.

### 📄 Motor de Exportación Multi-Formato

  * **📘 Microsoft Word:** Reportes maquetados profesionalmente con soporte Markdown.
  * **📕 Adobe PDF:** Generación nativa con **Doble Diccionario de Resaltado**:
      * *Diccionario Técnico:* Negritas automáticas en `XSS`, `RCE`, `Payloads`, `CVEs`, etc.
      * *Diccionario Ejecutivo:* Resaltado estratégico de `Confidencialidad`, `RGPD`, `Riesgo Reputacional`, etc.
  * **📗 Microsoft Excel:** Tabla de hallazgos con código de colores basado en el **Risk Score (1.0 - 10.0)**.

### 🔒 Seguridad y OPSEC

  * **ZIP Seguro:** Empaquetado final de reportes y evidencias crudas en un archivo comprimido con cifrado **AES-256 de grado militar**.
  * **Privacidad Total:** Arquitectura diseñada para evitar el envío de datos sensibles (IPs, nombres de cliente) a la nube.

-----

## 🛠️ Instalación y Compilación

La aplicación es multiplataforma y genera instaladores nativos.

### Requisitos previos

```bash
pip install pyinstaller pyzipper customtkinter fpdf python-docx pandas openpyxl requests
```

-----

## 📁 Estructura de Datos

Para garantizar la persistencia y evitar problemas de permisos, la base de datos y las configuraciones se alojan en la carpeta de usuario:

  * **Windows/Linux:** `~/Downloads/PwnDocDesktop/`

-----

## ✒️ Autor

  * **Roberto Tejado Busto** - *Desarrollo Integral* - © 2026

> **Nota:** Este software ha sido desarrollado para uso profesional en entornos controlados y auditorías autorizadas. El autor no se hace responsable del uso indebido de la herramienta.

-----

🚀🔥
