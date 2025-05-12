# 🧠 Nila - Chatbot para Gestión de Reservas

Nila es un chatbot interactivo desarrollado en JavaScript que permite a los usuarios realizar acciones como:

- Consultar reservas por fecha o día actual
- Descargar reservas en PDF por mes
- Crear nuevas reservas paso a paso
- Mostrar respuestas automáticas según una base de conocimiento JSON
- Limpiar el historial del chat con cuenta atrás de "autodestrucción"
- Acceder directamente al calendario (`http://localhost:5173/nueva`)

---

## 🚀 Funcionalidades principales

| Función                      | Descripción                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `respuestas.json`           | Contiene las frases clave y respuestas de Nila en castellano y euskera     |
| Mensajes en el chat         | Soporte para mensajes del usuario y del bot, con íconos y scroll automático |
| Detección de fechas         | Nila entiende frases como `13 de mayo` o `13/05`                            |
| Descarga de PDF             | Al pedir un "documento de reservas del mes", se genera y descarga automáticamente |
| Creación de reservas        | Conversación guiada paso a paso (tipo de recurso, motivo, fechas y horas)  |
| Recurso con o sin cantidad  | Si el recurso es tipo carpa, silla, etc., pide cantidad; si es sala o plaza, no |
| Animación de autodestrucción| Mensaje animado de 3 segundos para vaciar el historial del chat             |
| Acceso directo al calendario| Frases como `abrir calendario` abren automáticamente la URL `http://localhost:5173/nueva` |

---

## 📁 Estructura del proyecto

📂 NilaChat/
│
├── index.html
├── style.css
├── chatbot.js # Toda la lógica del bot
├── respuestas.json # Conjunto de palabras clave y respuestas automáticas
├── NilaTransparent.png


---

## 🛠️ Tecnologías utilizadas

- JavaScript (ES6+)
- HTML5
- CSS3
- jsPDF (para exportar PDF)
- LocalStorage (para guardar datos temporales del usuario)
- Bootstrap (para botones y estilos)

📸 Capturas

![image](https://github.com/user-attachments/assets/cf190f2f-a24c-4ca4-9133-d6d220359e36)
![image](https://github.com/user-attachments/assets/9298a2dc-e863-4481-9f2d-ff32cb5c4018)
![image](https://github.com/user-attachments/assets/6ba7127b-faf5-46ed-8883-aabb81db94a0)
![image](https://github.com/user-attachments/assets/f63dd7af-246d-4367-91d6-ca1edd0a45e5)

📬 Contacto
Desarrollado por Tu Nombre o GitHub Aitor Cobo Fariñas aitorcobo01@gmail.com

📄 Licencia

# ⚠️ Licencia de Uso Restringido

Este software, denominado **Nila - Chatbot para Gestión de Reservas**, es propiedad exclusiva del autor. **No se permite su redistribución, modificación, copia o uso comercial** sin consentimiento explícito y por escrito del titular de los derechos.

Queda prohibido:

- La reproducción total o parcial del código fuente o de sus componentes.
- La modificación, adaptación o descompilación del software.
- La incorporación del chatbot o cualquiera de sus funciones en proyectos comerciales o públicos sin autorización expresa.
- Su redistribución por medios electrónicos, físicos o en línea.

Este software ha sido desarrollado con fines educativos y profesionales internos. **El uso está limitado al entorno de trabajo privado del desarrollador y/o de la entidad para la que ha sido creado.**

### 📬 Contacto para autorización

Si deseas utilizar este chatbot para otros fines o tienes dudas sobre esta licencia, puedes contactar al autor mediante GitHub o correo electrónico; aitorcobo01@gmail.com

---

© 2025 NilaChat - Todos los derechos reservados.





